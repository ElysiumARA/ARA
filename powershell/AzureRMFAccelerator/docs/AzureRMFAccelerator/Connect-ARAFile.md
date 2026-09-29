---
document type: cmdlet
external help file: AzureRMFAgent.Module.dll-Help.xml
HelpUri: ''
Locale: en-US
Module Name: AzureRMFAgent
ms.date: 09/15/2026
PlatyPS schema version: 2024-05-01
title: Connect-ARAFile
---

# Connect-ARAFile

## SYNOPSIS

Connect operation for ARAFile

## SYNTAX

### __AllParameterSets

```
Connect-ARAFile [[-System] <string>] [[-Version] <string>]
```

## ALIASES

This cmdlet has the following aliases,
  {{Insert list of aliases}}

## DESCRIPTION

Creates the ARA context for a directory and optionally connects to an existing ARA file.

## EXAMPLES

### Example 1

Connect-ARAFile -System "MySystem" -Version "1.0"

This cmdlet must be called before using any other ARA cmdlets.
It initializes the context
            that provides access to the ARA file repository.
If System and Version are provided,
            it also loads the corresponding ARA file.

## PARAMETERS

### -System

The system name of the ARA file to connect to.
Optional; if not provided, only context is initialized.

```yaml
Type: System.String
DefaultValue: ''
SupportsWildcards: false
Aliases: []
ParameterSets:
- Name: (All)
  Position: 1
  IsRequired: false
  ValueFromPipeline: false
  ValueFromPipelineByPropertyName: true
  ValueFromRemainingArguments: false
DontShow: false
AcceptedValues: []
HelpMessage: ''
```

### -Version

The version of the ARA file to connect to.
Optional; required if System is provided.

```yaml
Type: System.String
DefaultValue: ''
SupportsWildcards: false
Aliases: []
ParameterSets:
- Name: (All)
  Position: 2
  IsRequired: false
  ValueFromPipeline: false
  ValueFromPipelineByPropertyName: true
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

### System.String

{{ Fill in the Description }}

## OUTPUTS

### System.Object

{{ Fill in the Description }}

### AzureRMFAgent.Core.ARAFile

Root container for all ARA data.
Represents the complete ARA document structure.

### AzureRMFAgent.Core.ARAResult

{{ Fill in the Description }}

## NOTES




## RELATED LINKS

- [Online Version]()
- [Online Version]()
- [Online Version]()
- [Online Version]()
- [Online Version]()
