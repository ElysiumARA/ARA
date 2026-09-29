---
document type: cmdlet
external help file: AzureRMFAgent.Module.dll-Help.xml
HelpUri: ''
Locale: en-US
Module Name: AzureRMFAgent
ms.date: 09/15/2026
PlatyPS schema version: 2024-05-01
title: Remove-ARAArchitectureDiagram
---

# Remove-ARAArchitectureDiagram

## SYNOPSIS

Remove operation for ARAArchitectureDiagram

## SYNTAX

### __AllParameterSets

```
Remove-ARAArchitectureDiagram -Name <string>
```

## ALIASES

This cmdlet has the following aliases,
  {{Insert list of aliases}}

## DESCRIPTION

Removes an architecture diagram from the connected ARA file.

## EXAMPLES

### Example 1

Remove-ARAArchitectureDiagram -Name "MyDiagram"

Deletes the existing ArchitectureDiagram object from the currently connected ARA file.

## PARAMETERS

### -Name

The name of the architecture diagram to remove.
Mandatory.

```yaml
Type: System.String
DefaultValue: ''
SupportsWildcards: false
Aliases: []
ParameterSets:
- Name: (All)
  Position: Named
  IsRequired: true
  ValueFromPipeline: false
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

## OUTPUTS

### AzureRMFAgent.Core.ARAResult

Result of running a command.

## NOTES




## RELATED LINKS

- [Online Version]()
- [Online Version]()
- [Online Version]()
- [Online Version]()
