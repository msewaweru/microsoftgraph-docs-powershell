---
external help file: Microsoft.Graph.Beta.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.Beta.DeviceManagement.Actions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devicemanagement.actions/update-mgbetadevicemanagementgrouppolicyuploadeddefinitionfilelanguagefile
schema: 2.0.0
---

# Update-MgBetaDeviceManagementGroupPolicyUploadedDefinitionFileLanguageFile

## SYNOPSIS
Invoke action updateLanguageFiles

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgBetaDeviceManagementGroupPolicyUploadedDefinitionFileLanguageFile
 -GroupPolicyUploadedDefinitionFileId <String> [-ResponseHeadersVariable <String>]
 [-AdditionalProperties <Hashtable>]
 [-GroupPolicyUploadedLanguageFiles <IMicrosoftGraphGroupPolicyUploadedLanguageFile[]>]
 [-Headers <IDictionary>] [-PassThru] [-ProgressAction <ActionPreference>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Update
```
Update-MgBetaDeviceManagementGroupPolicyUploadedDefinitionFileLanguageFile
 -GroupPolicyUploadedDefinitionFileId <String>
 -BodyParameter <IPathsYx6FbvDevicemanagementGrouppolicyuploadeddefinitionfilesGrouppolicyuploadeddefinitionfileIdMicrosoftGraphUpdatelanguagefilesPostRequestbodyContentApplicationJsonSchema>
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-PassThru] [-ProgressAction <ActionPreference>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgBetaDeviceManagementGroupPolicyUploadedDefinitionFileLanguageFile
 -InputObject <IDeviceManagementActionsIdentity> [-ResponseHeadersVariable <String>]
 [-AdditionalProperties <Hashtable>]
 [-GroupPolicyUploadedLanguageFiles <IMicrosoftGraphGroupPolicyUploadedLanguageFile[]>]
 [-Headers <IDictionary>] [-PassThru] [-ProgressAction <ActionPreference>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgBetaDeviceManagementGroupPolicyUploadedDefinitionFileLanguageFile
 -InputObject <IDeviceManagementActionsIdentity>
 -BodyParameter <IPathsYx6FbvDevicemanagementGrouppolicyuploadeddefinitionfilesGrouppolicyuploadeddefinitionfileIdMicrosoftGraphUpdatelanguagefilesPostRequestbodyContentApplicationJsonSchema>
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-PassThru] [-ProgressAction <ActionPreference>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action updateLanguageFiles

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter

To construct, see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IPathsYx6FbvDevicemanagementGrouppolicyuploadeddefinitionfilesGrouppolicyuploadeddefinitionfileIdMicrosoftGraphUpdatelanguagefilesPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -GroupPolicyUploadedDefinitionFileId
The unique identifier of groupPolicyUploadedDefinitionFile

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GroupPolicyUploadedLanguageFiles

To construct, see NOTES section for GROUPPOLICYUPLOADEDLANGUAGEFILES properties and create a hash table.

```yaml
Type: IMicrosoftGraphGroupPolicyUploadedLanguageFile[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
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

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IDeviceManagementActionsIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
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

### Microsoft.Graph.Beta.PowerShell.Models.IDeviceManagementActionsIdentity
### Microsoft.Graph.Beta.PowerShell.Models.IPathsYx6FbvDevicemanagementGrouppolicyuploadeddefinitionfilesGrouppolicyuploadeddefinitionfileIdMicrosoftGraphUpdatelanguagefilesPostRequestbodyContentApplicationJsonSchema
### System.Collections.IDictionary
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER `<IPathsYx6FbvDevicemanagementGrouppolicyuploadeddefinitionfilesGrouppolicyuploadeddefinitionfileIdMicrosoftGraphUpdatelanguagefilesPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[GroupPolicyUploadedLanguageFiles <IMicrosoftGraphGroupPolicyUploadedLanguageFile- `[]`>]`: 
    - `[Content <Byte- `[]`>]`: The contents of the uploaded ADML file.
    - `[FileName <String>]`: The file name of the uploaded ADML file.
    - `[Id <String>]`: Key of the entity.
    - `[LanguageCode <String>]`: The language code of the uploaded ADML file.
    - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.

GROUPPOLICYUPLOADEDLANGUAGEFILES `<IMicrosoftGraphGroupPolicyUploadedLanguageFile- `[]`>`: .
  - `[Content <Byte- `[]`>]`: The contents of the uploaded ADML file.
  - `[FileName <String>]`: The file name of the uploaded ADML file.
  - `[Id <String>]`: Key of the entity.
  - `[LanguageCode <String>]`: The language code of the uploaded ADML file.
  - `[LastModifiedDateTime <DateTime?>]`: The date and time the entity was last modified.

INPUTOBJECT `<IDeviceManagementActionsIdentity>`: Identity Parameter
  - `[AlertRecordId <String>]`: The unique identifier of alertRecord
  - `[AndroidDeviceOwnerEnrollmentProfileId <String>]`: The unique identifier of androidDeviceOwnerEnrollmentProfile
  - `[AndroidForWorkEnrollmentProfileId <String>]`: The unique identifier of androidForWorkEnrollmentProfile
  - `[AppLogCollectionRequestId <String>]`: The unique identifier of appLogCollectionRequest
  - `[AppleUserInitiatedEnrollmentProfileId <String>]`: The unique identifier of appleUserInitiatedEnrollmentProfile
  - `[CertificateConnectorDetailsId <String>]`: The unique identifier of certificateConnectorDetails
  - `[CloudPcDeviceImageId <String>]`: The unique identifier of cloudPcDeviceImage
  - `[CloudPcId <String>]`: The unique identifier of cloudPC
  - `[CloudPcOnPremisesConnectionId <String>]`: The unique identifier of cloudPcOnPremisesConnection
  - `[CloudPcProvisioningPolicyId <String>]`: The unique identifier of cloudPcProvisioningPolicy
  - `[CloudPcUserSettingId <String>]`: The unique identifier of cloudPcUserSetting
  - `[DataSharingConsentId <String>]`: The unique identifier of dataSharingConsent
  - `[DepOnboardingSettingId <String>]`: The unique identifier of depOnboardingSetting
  - `[DeviceCompliancePolicyId <String>]`: The unique identifier of deviceCompliancePolicy
  - `[DeviceComplianceScriptId <String>]`: The unique identifier of deviceComplianceScript
  - `[DeviceConfigurationId <String>]`: The unique identifier of deviceConfiguration
  - `[DeviceCustomAttributeShellScriptId <String>]`: The unique identifier of deviceCustomAttributeShellScript
  - `[DeviceEnrollmentConfigurationId <String>]`: The unique identifier of deviceEnrollmentConfiguration
  - `[DeviceHealthScriptId <String>]`: The unique identifier of deviceHealthScript
  - `[DeviceLogCollectionResponseId <String>]`: The unique identifier of deviceLogCollectionResponse
  - `[DeviceManagementCompliancePolicyId <String>]`: The unique identifier of deviceManagementCompliancePolicy
  - `[DeviceManagementConfigurationPolicyId <String>]`: The unique identifier of deviceManagementConfigurationPolicy
  - `[DeviceManagementExchangeConnectorId <String>]`: The unique identifier of deviceManagementExchangeConnector
  - `[DeviceManagementIntentId <String>]`: The unique identifier of deviceManagementIntent
  - `[DeviceManagementPartnerId <String>]`: The unique identifier of deviceManagementPartner
  - `[DeviceManagementResourceAccessProfileBaseId <String>]`: The unique identifier of deviceManagementResourceAccessProfileBase
  - `[DeviceManagementReusablePolicySettingId <String>]`: The unique identifier of deviceManagementReusablePolicySetting
  - `[DeviceManagementScriptId <String>]`: The unique identifier of deviceManagementScript
  - `[DeviceManagementTemplateId <String>]`: The unique identifier of deviceManagementTemplate
  - `[DeviceManagementTemplateId1 <String>]`: The unique identifier of deviceManagementTemplate
  - `[DeviceShellScriptId <String>]`: The unique identifier of deviceShellScript
  - `[EmbeddedSimActivationCodePoolId <String>]`: The unique identifier of embeddedSIMActivationCodePool
  - `[EnrollmentProfileId <String>]`: The unique identifier of enrollmentProfile
  - `[GroupPolicyConfigurationId <String>]`: The unique identifier of groupPolicyConfiguration
  - `[GroupPolicyMigrationReportId <String>]`: The unique identifier of groupPolicyMigrationReport
  - `[GroupPolicyUploadedDefinitionFileId <String>]`: The unique identifier of groupPolicyUploadedDefinitionFile
  - `[HardwareConfigurationId <String>]`: The unique identifier of hardwareConfiguration
  - `[IntuneBrandingProfileId <String>]`: The unique identifier of intuneBrandingProfile
  - `[ManagedDeviceId <String>]`: The unique identifier of managedDevice
  - `[MicrosoftTunnelServerId <String>]`: The unique identifier of microsoftTunnelServer
  - `[MicrosoftTunnelServerLogCollectionResponseId <String>]`: The unique identifier of microsoftTunnelServerLogCollectionResponse
  - `[MicrosoftTunnelSiteId <String>]`: The unique identifier of microsoftTunnelSite
  - `[MobileAppTroubleshootingEventId <String>]`: The unique identifier of mobileAppTroubleshootingEvent
  - `[NotificationMessageTemplateId <String>]`: The unique identifier of notificationMessageTemplate
  - `[OperationApprovalRequestId <String>]`: The unique identifier of operationApprovalRequest
  - `[PrivilegeManagementElevationRequestId <String>]`: The unique identifier of privilegeManagementElevationRequest
  - `[RemoteAssistancePartnerId <String>]`: The unique identifier of remoteAssistancePartner
  - `[RoleScopeTagId <String>]`: The unique identifier of roleScopeTag
  - `[WindowsAutopilotDeploymentProfileId <String>]`: The unique identifier of windowsAutopilotDeploymentProfile
  - `[WindowsAutopilotDeviceIdentityId <String>]`: The unique identifier of windowsAutopilotDeviceIdentity
  - `[WindowsDriverUpdateProfileId <String>]`: The unique identifier of windowsDriverUpdateProfile
  - `[WindowsFeatureUpdateProfileId <String>]`: The unique identifier of windowsFeatureUpdateProfile
  - `[WindowsQualityUpdatePolicyId <String>]`: The unique identifier of windowsQualityUpdatePolicy
  - `[WindowsQualityUpdateProfileId <String>]`: The unique identifier of windowsQualityUpdateProfile
  - `[ZebraFotaDeploymentId <String>]`: The unique identifier of zebraFotaDeployment

## RELATED LINKS

[https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devicemanagement.actions/update-mgbetadevicemanagementgrouppolicyuploadeddefinitionfilelanguagefile](https://learn.microsoft.com/powershell/module/microsoft.graph.beta.devicemanagement.actions/update-mgbetadevicemanagementgrouppolicyuploadeddefinitionfilelanguagefile)
























