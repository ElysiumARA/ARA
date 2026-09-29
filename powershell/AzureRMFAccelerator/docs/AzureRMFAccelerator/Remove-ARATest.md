---
document type: cmdlet
external help file: AzureRMFAgent.Module.dll-Help.xml
HelpUri: ''
Locale: en-US
Module Name: AzureRMFAgent
ms.date: 09/15/2026
PlatyPS schema version: 2024-05-01
title: Remove-ARATest
---

# Remove-ARATest

## SYNOPSIS

Remove operation for ARATest

## SYNTAX

### __AllParameterSets

```
Remove-ARATest -Id <string>
```

## ALIASES

This cmdlet has the following aliases,
  {{Insert list of aliases}}

## DESCRIPTION

Removes a test configuration from the connected ARA file.

## EXAMPLES

### Example 1

Remove-ARATest -Id "Test1"

Deletes the existing Test object from the currently connected ARA file.

## PARAMETERS

### -Id

{{ Fill Id Description }}

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
