---
external help file: Microsoft.Graph.Beta.Education-help.xml
Module Name: Microsoft.Graph.Beta.Education
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.education/new-mgbetaeducationsynchronizationprofile
schema: 2.0.0
---

# New-MgBetaEducationSynchronizationProfile

## SYNOPSIS
Create new navigation property to synchronizationProfiles for education

## SYNTAX

### CreateExpanded (Default)
```
New-MgBetaEducationSynchronizationProfile [-ResponseHeadersVariable <String>]
 [-AdditionalProperties <Hashtable>] [-DataProvider <Hashtable>] [-DisplayName <String>]
 [-Errors <IMicrosoftGraphEducationSynchronizationError[]>] [-ExpirationDate <DateTime>]
 [-HandleSpecialCharacterConstraint] [-Id <String>] [-IdentitySynchronizationConfiguration <Hashtable>]
 [-LicensesToAssign <IMicrosoftGraphEducationSynchronizationLicenseAssignment[]>]
 [-ProfileStatus <IMicrosoftGraphEducationSynchronizationProfileStatus>] [-State <String>]
 [-Headers <IDictionary>] [-ProgressAction <ActionPreference>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Create
```
New-MgBetaEducationSynchronizationProfile -BodyParameter <IMicrosoftGraphEducationSynchronizationProfile>
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-ProgressAction <ActionPreference>] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Create new navigation property to synchronizationProfiles for education

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
educationSynchronizationProfile
To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphEducationSynchronizationProfile
Parameter Sets: Create
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -DataProvider
educationSynchronizationDataProvider

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Name of the configuration profile for syncing identities.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Errors
All errors associated with this synchronization profile.
To construct, see NOTES section for ERRORS properties and create a hash table.

```yaml
Type: IMicrosoftGraphEducationSynchronizationError[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpirationDate
The date the profile should be considered expired and cease syncing.
Provide the date in YYYY-MM-DD format, following ISO 8601.
Maximum value is 18 months from profile creation.
(optional)

```yaml
Type: DateTime
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -HandleSpecialCharacterConstraint
Determines if School Data Sync should automatically replace unsupported special characters while syncing from source.

```yaml
Type: SwitchParameter
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Headers
Optional headers that will be added to the request.

```yaml
Type: IDictionary
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Id
The unique identifier for an entity.
Read-only.

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IdentitySynchronizationConfiguration
educationIdentitySynchronizationConfiguration

```yaml
Type: Hashtable
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LicensesToAssign
License setup configuration.
To construct, see NOTES section for LICENSESTOASSIGN properties and create a hash table.

```yaml
Type: IMicrosoftGraphEducationSynchronizationLicenseAssignment[]
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProfileStatus
educationSynchronizationProfileStatus
To construct, see NOTES section for PROFILESTATUS properties and create a hash table.

```yaml
Type: IMicrosoftGraphEducationSynchronizationProfileStatus
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProgressAction
{{ Fill ProgressAction Description }}

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: proga

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResponseHeadersVariable
Optional Response Headers Variable.

```yaml
Type: String
Parameter Sets: (All)
Aliases: RHV

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -State
educationSynchronizationProfileState

```yaml
Type: String
Parameter Sets: CreateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphEducationSynchronizationProfile
### System.Collections.IDictionary
## OUTPUTS

### Microsoft.Graph.Beta.PowerShell.Models.IMicrosoftGraphEducationSynchronizationProfile
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER `<IMicrosoftGraphEducationSynchronizationProfile>`: educationSynchronizationProfile
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity.
Read-only.
  - `[DataProvider <IMicrosoftGraphEducationSynchronizationDataProvider>]`: educationSynchronizationDataProvider
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[DisplayName <String>]`: Name of the configuration profile for syncing identities.
  - `[Errors <IMicrosoftGraphEducationSynchronizationError- `[]`>]`: All errors associated with this synchronization profile.
    - `[Id <String>]`: The unique identifier for an entity.
Read-only.
    - `[EntryType <String>]`: Represents the sync entity (school, section, student, teacher).
    - `[ErrorCode <String>]`: Represents the error code for this error.
    - `[ErrorMessage <String>]`: Contains a description of the error.
    - `[JoiningValue <String>]`: The unique identifier for the entry.
    - `[RecordedDateTime <DateTime?>]`: The time of occurrence of this error.
    - `[ReportableIdentifier <String>]`: The identifier of this error entry.
  - `[ExpirationDate <DateTime?>]`: The date the profile should be considered expired and cease syncing.
Provide the date in YYYY-MM-DD format, following ISO 8601.
Maximum value is 18 months from profile creation. 
(optional)
  - `[HandleSpecialCharacterConstraint <Boolean?>]`: Determines if School Data Sync should automatically replace unsupported special characters while syncing from source.
  - `[IdentitySynchronizationConfiguration <IMicrosoftGraphEducationIdentitySynchronizationConfiguration>]`: educationIdentitySynchronizationConfiguration
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[LicensesToAssign <IMicrosoftGraphEducationSynchronizationLicenseAssignment- `[]`>]`: License setup configuration.
    - `[AppliesTo <String>]`: educationUserRole
    - `[SkuIds <String- `[]`>]`: Represents the SKU identifiers of the licenses to assign.
  - `[ProfileStatus <IMicrosoftGraphEducationSynchronizationProfileStatus>]`: educationSynchronizationProfileStatus
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[Id <String>]`: The unique identifier for an entity.
Read-only.
    - `[ErrorCount <Int64?>]`: Number of errors during synchronization.
    - `[LastActivityDateTime <DateTime?>]`: Date and time when most recent changes were observed in the profile.
    - `[LastSynchronizationDateTime <DateTime?>]`: Date and time of the most recent successful synchronization.
    - `[Status <String>]`: educationSynchronizationStatus
    - `[StatusMessage <String>]`: Status message for the synchronization stage of the current profile.
  - `[State <String>]`: educationSynchronizationProfileState

ERRORS `<IMicrosoftGraphEducationSynchronizationError- `[]`>`: All errors associated with this synchronization profile.
  - `[Id <String>]`: The unique identifier for an entity.
Read-only.
  - `[EntryType <String>]`: Represents the sync entity (school, section, student, teacher).
  - `[ErrorCode <String>]`: Represents the error code for this error.
  - `[ErrorMessage <String>]`: Contains a description of the error.
  - `[JoiningValue <String>]`: The unique identifier for the entry.
  - `[RecordedDateTime <DateTime?>]`: The time of occurrence of this error.
  - `[ReportableIdentifier <String>]`: The identifier of this error entry.

LICENSESTOASSIGN `<IMicrosoftGraphEducationSynchronizationLicenseAssignment- `[]`>`: License setup configuration.
  - `[AppliesTo <String>]`: educationUserRole
  - `[SkuIds <String- `[]`>]`: Represents the SKU identifiers of the licenses to assign.

PROFILESTATUS `<IMicrosoftGraphEducationSynchronizationProfileStatus>`: educationSynchronizationProfileStatus
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[Id <String>]`: The unique identifier for an entity.
Read-only.
  - `[ErrorCount <Int64?>]`: Number of errors during synchronization.
  - `[LastActivityDateTime <DateTime?>]`: Date and time when most recent changes were observed in the profile.
  - `[LastSynchronizationDateTime <DateTime?>]`: Date and time of the most recent successful synchronization.
  - `[Status <String>]`: educationSynchronizationStatus
  - `[StatusMessage <String>]`: Status message for the synchronization stage of the current profile.

## RELATED LINKS

[https://learn.microsoft.com/powershell/module/microsoft.graph.beta.education/new-mgbetaeducationsynchronizationprofile](https://learn.microsoft.com/powershell/module/microsoft.graph.beta.education/new-mgbetaeducationsynchronizationprofile)
























