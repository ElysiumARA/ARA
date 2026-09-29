---
document type: cmdlet
external help file: AzureRMFAgent.Module.dll-Help.xml
HelpUri: ''
Locale: en-US
Module Name: AzureRMFAgent
ms.date: 09/15/2026
PlatyPS schema version: 2024-05-01
title: Get-ARASystem
---

# Get-ARASystem

## SYNOPSIS

Get operation for ARASystem

## SYNTAX

### __AllParameterSets

```
Get-ARASystem
```

## ALIASES

This cmdlet has the following aliases,
  {{Insert list of aliases}}

## DESCRIPTION

Gets the ARA system metadata (system name, version, customer, RMF provider information).

## EXAMPLES

### Example 1

Get-ARASystem

Returns the SystemInfo object from the currently connected ARA file.
            Connect-ARAFile must be called first to load an ARA file.

## PARAMETERS

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable,
-InformationAction, -InformationVariable, -OutBuffer, -OutVariable, -PipelineVariable,
-ProgressAction, -Verbose, -WarningAction, and -WarningVariable. For more information, see
[about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### System.Object

{{ Fill in the Description }}

### AzureRMFAgent.Core.SystemInfo

Contains basic metadata information about the system being modeled.

## NOTES




## RELATED LINKS

- [Online Version]()
- [Online Version]()
- [Online Version]()
- [Online Version]()
- [Online Version]()
