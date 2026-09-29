---
document type: cmdlet
external help file: AzureRMFAgent.Module.dll-Help.xml
HelpUri: ''
Locale: en-US
Module Name: AzureRMFAgent
ms.date: 09/15/2026
PlatyPS schema version: 2024-05-01
title: Set-ARAOperations
---

# Set-ARAOperations

## SYNOPSIS

Set operation for ARAOperations

## SYNTAX

### __AllParameterSets

```
Set-ARAOperations -Operations <Operations>
```

## ALIASES

This cmdlet has the following aliases,
  {{Insert list of aliases}}

## DESCRIPTION

Updates the operations settings in the connected ARA file.

## EXAMPLES

### Example 1

Set-ARAOperations -Operations $operationsObject

Changes are stored in memory until saved using Save-ARAFile.

## PARAMETERS

### -Operations

The Operations object to update.
If provided, other parameters are ignored.

```yaml
Type: AzureRMFAgent.Core.Operations
DefaultValue: ''
SupportsWildcards: false
Aliases: []
ParameterSets:
- Name: (All)
  Position: Named
  IsRequired: true
  ValueFromPipeline: true
  ValueFromPipelineByPropertyName: false
  ValueFromRemainingArguments: false
DontShow: false
AcceptedValues: []
HelpMessage: ''
```

### CommonParameters

This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable,
-InformationAction, -InformationVariable, -OutBuffer, -OutVariable, -PipelineVariable,
-ProgressAction, -Verbose, -WarningAction, and -WarningVariable. For more information, see
[about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### AzureRMFAgent.Core.Operations

Information about the operations of the system being modeled.

## OUTPUTS

### AzureRMFAgent.Core.ARAResult

Result of running a command.

## NOTES




## RELATED LINKS

- [Online Version]()
- [Online Version]()
- [Online Version]()
- [Online Version]()
