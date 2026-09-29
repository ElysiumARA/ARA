---
document type: cmdlet
external help file: AzureRMFAgent.Module.dll-Help.xml
HelpUri: ''
Locale: en-US
Module Name: AzureRMFAgent
ms.date: 09/15/2026
PlatyPS schema version: 2024-05-01
title: Set-ARAArtifact
---

# Set-ARAArtifact

## SYNOPSIS

{{ Fill in the Synopsis }}

## SYNTAX

### ArtifactType (Default)

```
Set-ARAArtifact -ArtifactType <ArtifactContent+ArtifactTypes> [-ArtifactUri <string>]
 [-TemplateUri <string>]
```

### Schema

```
Set-ARAArtifact -ArtifactSchemaJsonUri <string> [-ArtifactUri <string>] [-TemplateUri <string>]
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

### -ArtifactUri

{{ Fill ArtifactUri Description }}

```yaml
Type: System.String
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

### -TemplateUri

{{ Fill TemplateUri Description }}

```yaml
Type: System.String
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

## OUTPUTS

### AzureRMFAgent.Core.ARAResult

{{ Fill in the Description }}

## NOTES

{{ Fill in the Notes }}

## RELATED LINKS

{{ Fill in the related links here }}

