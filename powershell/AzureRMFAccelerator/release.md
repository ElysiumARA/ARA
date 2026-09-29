# Release Notes

## 1.1.4 — Initial Release

First public release of the **AzureRMFAgent** PowerShell module.

### What's included

The module provides a full set of cmdlets for creating, loading, updating, validating, and saving ARA JSON files — the structured system definition format used by the Azure RMF Agent.

### Available commands

The module includes the following command groups as documented in the cmdlet reference and help files.

#### File / session / schema management
`New-ARAFile` · `Connect-ARAContext` · `Connect-ARAFile` · `Export-ARAFile` · `Save-ARAFile` · `Test-ARAFile` · `Test-ARASchema` · `Get-ARAArtifactSchema`

#### System metadata / operations
`Get-ARASystem` · `Set-ARASystem` · `Get-ARAOperations` · `Set-ARAOperations` · `Remove-ARAOperations` · `Get-ARADefinition`

#### Artifact definitions
`New-ARAArtifact` · `Set-ARAArtifact` · `Add-ARAArtifactContent` · `Get-ARAArtifactContent` · `Set-ARAArtifactContent` · `Remove-ARAArtifactContent` · `Add-ARAArtifactManifest` · `Get-ARAArtifactManifest` · `Remove-ARAArtifactManifest` · `Add-ARAArtifactTemplate` · `Remove-ARAArtifactTemplate`

#### Roles
`New-ARARole` · `Get-ARARole` · `Add-ARARole` · `Set-ARARole` · `Remove-ARARole`

#### Environments
`New-ARAEnvironment` · `Get-ARAEnvironment` · `Add-ARAEnvironment` · `Set-ARAEnvironment` · `Remove-ARAEnvironment`

#### Resource groups and resource roles
`New-ARAResourceGroup` · `New-ARAResourceRole`

#### Resources
`New-ARAResource` · `Get-ARAResource` · `Add-ARAResource` · `Set-ARAResource` · `Remove-ARAResource`

#### Linked resources
`New-ARALinkedResource` · `Add-ARALinkedResource` · `Set-ARALinkedResource` · `Remove-ARALinkedResource`

#### Resource types
`New-ARAResourceType` · `Get-ARAResourceType` · `Add-ARAResourceType` · `Set-ARAResourceType` · `Remove-ARAResourceType`

#### Architecture and compliance objects
`Add-ARAArchitectureDiagram` · `Get-ARAArchitectureDiagram` · `Set-ARAArchitectureDiagram` · `Remove-ARAArchitectureDiagram` · `Add-ARABackupRecovery` · `Get-ARABackupRecovery` · `Set-ARABackupRecovery` · `Remove-ARABackupRecovery` · `Add-ARAChangeManagement` · `Get-ARAChangeManagement` · `Set-ARAChangeManagement` · `Remove-ARAChangeManagement` · `Add-ARAControl` · `Get-ARAControl` · `Set-ARAControl` · `Remove-ARAControl` · `Add-ARAMission` · `Get-ARAMission` · `Set-ARAMission` · `Remove-ARAMission` · `Add-ARARequirement` · `Get-ARARequirement` · `Set-ARARequirement` · `Remove-ARARequirement` · `Add-ARAScope` · `Get-ARAScope` · `Set-ARAScope` · `Remove-ARAScope` · `Add-ARASecurity` · `Get-ARASecurity` · `Set-ARASecurity` · `Remove-ARASecurity` · `Add-ARAServiceLevel` · `Get-ARAServiceLevel` · `Set-ARAServiceLevel` · `Remove-ARAServiceLevel` · `Add-ARASupport` · `Get-ARASupport` · `Set-ARASupport` · `Remove-ARASupport` · `Add-ARATest` · `Get-ARATest` · `Set-ARATest` · `Remove-ARATest`

#### Software catalog
`Get-ARASoftware` · `Add-ARASoftware` · `Set-ARASoftware` · `Remove-ARASoftware` · `New-ARASoftware`

#### STIGs
`New-ARAStig` · `Get-ARAStig` · `Add-ARAStig` · `Set-ARAStig` · `Remove-ARAStig`

#### Configuration strings
`New-ARAConfigurationString` · `Get-ARAConfigurationString` · `Add-ARAConfigurationString` · `Set-ARAConfigurationString` · `Remove-ARAConfigurationString`

#### Additional resource builders
`New-ARAIacModule`

### Requirements
- PowerShell 5.1 or later
- Internet access required when validating against the hosted schema (`https://` schema URI)

### Known limitations
- The module uses global session state (`$global:ARAFile`, `$global:path`). Only one ARA file can be active per session.
- `Test-ARAFile` performs structural JSON schema validation only; cross-reference integrity (e.g., role keys referenced by resources) is partially validated in-module but not covered by the schema itself.
