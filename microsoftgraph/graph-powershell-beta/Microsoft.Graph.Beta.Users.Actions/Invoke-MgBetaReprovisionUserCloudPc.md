---
external help file: Microsoft.Graph.Beta.Users.Actions-help.xml
Module Name: Microsoft.Graph.Beta.Users.Actions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.beta.users.actions/invoke-mgbetareprovisionusercloudpc
schema: 2.0.0
ms.subservice: cloud-pc
---

# Invoke-MgBetaReprovisionUserCloudPc

## SYNOPSIS
Reprovision a specific Cloud PC.

## SYNTAX

### ReprovisionExpanded (Default)
```
Invoke-MgBetaReprovisionUserCloudPc -CloudPcId <String> -UserId <String> [-ResponseHeadersVariable <String>]
 [-AdditionalProperties <Hashtable>] [-OSVersion <String>] [-UserAccountType <String>] [-Headers <IDictionary>]
 [-PassThru] [-ProgressAction <ActionPreference>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Reprovision
```
Invoke-MgBetaReprovisionUserCloudPc -CloudPcId <String> -UserId <String>
 -BodyParameter <IPaths1Yi5ZtbUsersUserIdCloudpcsCloudpcIdMicrosoftGraphReprovisionPostRequestbodyContentApplicationJsonSchema>
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-PassThru] [-ProgressAction <ActionPreference>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ReprovisionViaIdentityExpanded
```
Invoke-MgBetaReprovisionUserCloudPc -InputObject <IUsersActionsIdentity> [-ResponseHeadersVariable <String>]
 [-AdditionalProperties <Hashtable>] [-OSVersion <String>] [-UserAccountType <String>] [-Headers <IDictionary>]
 [-PassThru] [-ProgressAction <ActionPreference>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ReprovisionViaIdentity
```
Invoke-MgBetaReprovisionUserCloudPc -InputObject <IUsersActionsIdentity>
 -BodyParameter <IPaths1Yi5ZtbUsersUserIdCloudpcsCloudpcIdMicrosoftGraphReprovisionPostRequestbodyContentApplicationJsonSchema>
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-PassThru] [-ProgressAction <ActionPreference>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Reprovision a specific Cloud PC.

## EXAMPLES
### Example 1: Reprovision the cloudPC for the signed-in user

```powershell

Import-Module Microsoft.Graph.Beta.Users.Actions

# A UPN can also be used as -UserId.
Invoke-MgBetaReprovisionUserCloudPc -UserId $userId -CloudPCId $cloudPCId

```
This example will reprovision the cloudpc for the signed-in user


## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: ReprovisionExpanded, ReprovisionViaIdentityExpanded
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
Type: IPaths1Yi5ZtbUsersUserIdCloudpcsCloudpcIdMicrosoftGraphReprovisionPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Reprovision, ReprovisionViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CloudPcId
The unique identifier of cloudPC

```yaml
Type: String
Parameter Sets: ReprovisionExpanded, Reprovision
Aliases:

Required: True
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
Type: IUsersActionsIdentity
Parameter Sets: ReprovisionViaIdentityExpanded, ReprovisionViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -OSVersion
cloudPcOperatingSystem

```yaml
Type: String
Parameter Sets: ReprovisionExpanded, ReprovisionViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
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

### -UserAccountType
cloudPcUserAccountType

```yaml
Type: String
Parameter Sets: ReprovisionExpanded, ReprovisionViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
The unique identifier of user

```yaml
Type: String
Parameter Sets: ReprovisionExpanded, Reprovision
Aliases:

Required: True
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

### Microsoft.Graph.Beta.PowerShell.Models.IPaths1Yi5ZtbUsersUserIdCloudpcsCloudpcIdMicrosoftGraphReprovisionPostRequestbodyContentApplicationJsonSchema
### Microsoft.Graph.Beta.PowerShell.Models.IUsersActionsIdentity
### System.Collections.IDictionary
## OUTPUTS

### System.Boolean
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

BODYPARAMETER `<IPaths1Yi5ZtbUsersUserIdCloudpcsCloudpcIdMicrosoftGraphReprovisionPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[OSVersion <String>]`: cloudPcOperatingSystem
  - `[UserAccountType <String>]`: cloudPcUserAccountType

INPUTOBJECT `<IUsersActionsIdentity>`: Identity Parameter
  - `[AccessReviewInstanceId <String>]`: The unique identifier of accessReviewInstance
  - `[AccessReviewStageId <String>]`: The unique identifier of accessReviewStage
  - `[AppLogCollectionRequestId <String>]`: The unique identifier of appLogCollectionRequest
  - `[AuthenticationMethodId <String>]`: The unique identifier of authenticationMethod
  - `[CalendarId <String>]`: The unique identifier of calendar
  - `[ChatId <String>]`: The unique identifier of chat
  - `[ChatMessageId <String>]`: The unique identifier of chatMessage
  - `[ChatMessageId1 <String>]`: The unique identifier of chatMessage
  - `[CloudPcId <String>]`: The unique identifier of cloudPC
  - `[ContactFolderId <String>]`: The unique identifier of contactFolder
  - `[ContactFolderId1 <String>]`: The unique identifier of contactFolder
  - `[ContactId <String>]`: The unique identifier of contact
  - `[ContentTypeId <String>]`: The unique identifier of contentType
  - `[DeviceEnrollmentConfigurationId <String>]`: The unique identifier of deviceEnrollmentConfiguration
  - `[DeviceLogCollectionResponseId <String>]`: The unique identifier of deviceLogCollectionResponse
  - `[DocumentSetVersionId <String>]`: The unique identifier of documentSetVersion
  - `[DriveId <String>]`: The unique identifier of drive
  - `[DriveItemId <String>]`: The unique identifier of driveItem
  - `[DriveItemVersionId <String>]`: The unique identifier of driveItemVersion
  - `[EventId <String>]`: The unique identifier of event
  - `[EventId1 <String>]`: The unique identifier of event
  - `[JoinWebUrl <String>]`: Alternate key of onlineMeeting
  - `[ListItemId <String>]`: The unique identifier of listItem
  - `[ListItemVersionId <String>]`: The unique identifier of listItemVersion
  - `[MailFolderId <String>]`: The unique identifier of mailFolder
  - `[MailFolderId1 <String>]`: The unique identifier of mailFolder
  - `[ManagedDeviceId <String>]`: The unique identifier of managedDevice
  - `[MessageId <String>]`: The unique identifier of message
  - `[MobileAppTroubleshootingEventId <String>]`: The unique identifier of mobileAppTroubleshootingEvent
  - `[NotebookId <String>]`: The unique identifier of notebook
  - `[OnenotePageId <String>]`: The unique identifier of onenotePage
  - `[OnenoteSectionId <String>]`: The unique identifier of onenoteSection
  - `[OnlineMeetingId <String>]`: The unique identifier of onlineMeeting
  - `[OutlookTaskFolderId <String>]`: The unique identifier of outlookTaskFolder
  - `[OutlookTaskGroupId <String>]`: The unique identifier of outlookTaskGroup
  - `[OutlookTaskId <String>]`: The unique identifier of outlookTask
  - `[PermissionId <String>]`: The unique identifier of permission
  - `[PlannerPlanId <String>]`: The unique identifier of plannerPlan
  - `[SensitivityLabelId <String>]`: The unique identifier of sensitivityLabel
  - `[SubscriptionId <String>]`: The unique identifier of subscription
  - `[TeamsAppInstallationId <String>]`: The unique identifier of teamsAppInstallation
  - `[TodoTaskId <String>]`: The unique identifier of todoTask
  - `[TodoTaskListId <String>]`: The unique identifier of todoTaskList
  - `[UserId <String>]`: The unique identifier of user

## RELATED LINKS

[https://learn.microsoft.com/powershell/module/microsoft.graph.beta.users.actions/invoke-mgbetareprovisionusercloudpc](https://learn.microsoft.com/powershell/module/microsoft.graph.beta.users.actions/invoke-mgbetareprovisionusercloudpc)

[https://learn.microsoft.com/graph/api/cloudpc-reprovision?view=graph-rest-beta](https://learn.microsoft.com/graph/api/cloudpc-reprovision?view=graph-rest-beta)























