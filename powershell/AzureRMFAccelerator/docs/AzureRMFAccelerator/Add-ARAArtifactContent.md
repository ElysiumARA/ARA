---
document type: cmdlet
external help file: AzureRMFAgent.Module.dll-Help.xml
HelpUri: ''
Locale: en-US
Module Name: AzureRMFAgent
ms.date: 09/15/2026
PlatyPS schema version: 2024-05-01
title: Add-ARAArtifactContent
---

# Add-ARAArtifactContent

## SYNOPSIS

{{ Fill in the Synopsis }}

## SYNTAX

### ArtifactType (Default)

```
Add-ARAArtifactContent -ArtifactType <ArtifactContent+ArtifactTypes> -Data <List`1[Object]>
 [-Order <string[]>]
```

### Schema

```
Add-ARAArtifactContent -ArtifactSchemaJsonUri <string> -Data <List`1[Object]> [-Order <string[]>]
```

## ALIASES

This cmdlet has the following aliases,
  {{Insert list of aliases}}

## DESCRIPTION

{{ Fill in the Description }}

## EXAMPLES

### Example 1

{{ Add example description here }}

## PARAMETERS

### -ArtifactSchemaJsonUri

{{ Fill ArtifactSchemaJsonUri Description }}

```yaml
Type: System.String
DefaultValue: ''
SupportsWildcards: false
Aliases: []
ParameterSets:
- Name: Schema
  Position: Named
  IsRequired: true
  ValueFromPipeline: false
  ValueFromPipelineByPropertyName: false
  ValueFromRemainingArguments: false
DontShow: false
AcceptedValues: []
HelpMessage: ''
```

### -ArtifactType

{{ Fill ArtifactType Description }}

```yaml
Type: AzureRMFAgent.Core.Artifacts.ArtifactContent+ArtifactTypes
DefaultValue: ''
SupportsWildcards: false
Aliases: []
ParameterSets:
- Name: ArtifactType
  Position: Named
  IsRequired: true
  ValueFromPipeline: false
  ValueFromPipelineByPropertyName: false
  ValueFromRemainingArguments: false
DontShow: false
AcceptedValues: []
HelpMessage: ''
```

### -Data

{{ Fill Data Description }}

```yaml
Type: System.Collections.Generic.List`1[System.Object]
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

### -Order

{{ Fill Order Description }}

```yaml
Type: System.String[]
DefaultValue: ''
SupportsWildcards: false
Aliases: []
ParameterSets:
- Name: (All)
  Position: Named
  IsRequired: false
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

### System.Collections.Generic.List`1[[System.Object

{{ Fill in the Description }}

### System.Collections.Generic.List`1[[System.Object, mscorlib, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]

{{ Fill in the Description }}

## OUTPUTS

### AzureRMFAgent.Core.ARAResult

{{ Fill in the Description }}

## NOTES

{{ Fill in the Notes }}

## RELATED LINKS

{{ Fill in the related links here }}

