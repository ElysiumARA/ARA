![ARA Logo](ARA%20Logo.png)

# ARA PowerShell Module (`AzureRMFAgent`)

## Purpose
`AzureRMFAgent` is the domain module for managing Azure RMF Agent (ARA) data as strongly typed PowerShell objects and JSON.

It provides:
- Class models for ARA concepts (roles, environments, resource groups, resources, software, STIGs, and configuration strings)
- CRUD commands for each model
- File load/save workflows for ARA JSON files
- Validation helpers to validate ARA JSON content against schema

## What `AzureRMFAgent.psm1` manages
The module represents and persists:
- System metadata: `system`, `version`, `customer`, `$schema`
- Security roles and members
- Resource types
- Software catalog
- STIG mappings to resource types and appliers
- Environments, resource groups, resources, and linked resources
- Key/value configuration strings

## Key module behavior
- `Connect-ARAFile` loads an ARA JSON file into in-memory objects (`$global:ARAFile`).
- Most `Add-*`, `Set-*`, and `Remove-*` commands call `Save-ARAFile`.
- `Save-ARAFile` serializes the in-memory model back to JSON and reloads via `Connect-ARAFile` to keep references consistent.

## Main command groups

The complete list of available commands is maintained in the [cmdlet reference](reference.md). Refer to that page for the current command inventory and the [release notes](release.md) for version history.

## Typical usage flow
1. Import and connect:

```powershell
Install-Module -Name AzureRMFAgent -Scope CurrentUser
Import-Module AzureRMFAgent
Connect-ARAContext -Path .\files 
Connect-ARAFile -system "Contoso" -version "1.0.0"
```

2. Update data:

```powershell
Add-ARAEnvironment -Key "dev"
Add-ARAResourceType -Key "vm" -FriendlyName "Virtual Machine"
Add-ARARole -Key "admin" -Name "Administrator" -Group "Admins" -Active $true -Description "Admin role"
```

3. Validate:

```powershell
$result = Test-ARAFile
$result.IsValid
$result.Errors
```

## Notes
- `Connect-ARAContext` and `Connect-ARAFile` must be called before CRUD operations.
- Validation supports local schema files and HTTP(S) schema URLs.
