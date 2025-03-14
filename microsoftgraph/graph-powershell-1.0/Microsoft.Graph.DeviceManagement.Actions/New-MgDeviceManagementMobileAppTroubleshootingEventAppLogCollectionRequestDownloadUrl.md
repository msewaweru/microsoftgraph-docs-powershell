---
external help file: Microsoft.Graph.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Actions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.devicemanagement.actions/new-mgdevicemanagementmobileapptroubleshootingeventapplogcollectionrequestdownloadurl
schema: 2.0.0
ms.subservice: intune
---

# New-MgDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl

## SYNOPSIS
Not yet documented

> [!NOTE]
> To view the beta release of this cmdlet, view [New-MgBetaDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl](/powershell/module/Microsoft.Graph.Beta.DeviceManagement.Actions/New-MgBetaDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl?view=graph-powershell-beta)

## SYNTAX

### Create (Default)
```
New-MgDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl
 -AppLogCollectionRequestId <String> -MobileAppTroubleshootingEventId <String>
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-ProgressAction <ActionPreference>] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### CreateViaIdentity
```
New-MgDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl
 -InputObject <IDeviceManagementActionsIdentity> [-ResponseHeadersVariable <String>] [-Headers <IDictionary>]
 [-ProgressAction <ActionPreference>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Not yet documented

**Permissions**

| Permission type | Permissions (from least to most privileged) |
| --------------- | ------------------------------------------  |
| Delegated (work or school account) | Not supported |
| Delegated (personal Microsoft account) | Not supported |
| Application | DeviceManagementManagedDevices.Read.All, DeviceManagementManagedDevices.ReadWrite.All, DeviceManagementConfiguration.ReadWrite.All, DeviceManagementConfiguration.Read.All,  |

## EXAMPLES
### Example 1: Code snippet

```powershell

Import-Module Microsoft.Graph.DeviceManagement.Actions

New-MgDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl -MobileAppTroubleshootingEventId $mobileAppTroubleshootingEventId -AppLogCollectionRequestId $appLogCollectionRequestId

```
This example shows how to use the New-MgDeviceManagementMobileAppTroubleshootingEventAppLogCollectionRequestDownloadUrl Cmdlet.


## PARAMETERS

### -AppLogCollectionRequestId
The unique identifier of appLogCollectionRequest

```yaml
Type: String
Parameter Sets: Create
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
Type: IDeviceManagementActionsIdentity
Parameter Sets: CreateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -MobileAppTroubleshootingEventId
The unique identifier of mobileAppTroubleshootingEvent

```yaml
Type: String
Parameter Sets: Create
Aliases:

Required: True
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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementActionsIdentity
### System.Collections.IDictionary
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphAppLogCollectionDownloadDetails
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

INPUTOBJECT `<IDeviceManagementActionsIdentity>`: Identity Parameter
  - `[AppLogCollectionRequestId <String>]`: The unique identifier of appLogCollectionRequest
  - `[CloudPcId <String>]`: The unique identifier of cloudPC
  - `[CloudPcOnPremisesConnectionId <String>]`: The unique identifier of cloudPcOnPremisesConnection
  - `[CloudPcProvisioningPolicyId <String>]`: The unique identifier of cloudPcProvisioningPolicy
  - `[CloudPcUserSettingId <String>]`: The unique identifier of cloudPcUserSetting
  - `[DeviceCompliancePolicyId <String>]`: The unique identifier of deviceCompliancePolicy
  - `[DeviceConfigurationId <String>]`: The unique identifier of deviceConfiguration
  - `[DeviceEnrollmentConfigurationId <String>]`: The unique identifier of deviceEnrollmentConfiguration
  - `[DeviceLogCollectionResponseId <String>]`: The unique identifier of deviceLogCollectionResponse
  - `[DeviceManagementExchangeConnectorId <String>]`: The unique identifier of deviceManagementExchangeConnector
  - `[DeviceManagementPartnerId <String>]`: The unique identifier of deviceManagementPartner
  - `[ManagedDeviceId <String>]`: The unique identifier of managedDevice
  - `[MobileAppTroubleshootingEventId <String>]`: The unique identifier of mobileAppTroubleshootingEvent
  - `[NotificationMessageTemplateId <String>]`: The unique identifier of notificationMessageTemplate
  - `[RemoteAssistancePartnerId <String>]`: The unique identifier of remoteAssistancePartner
  - `[WindowsAutopilotDeviceIdentityId <String>]`: The unique identifier of windowsAutopilotDeviceIdentity

## RELATED LINKS

[https://learn.microsoft.com/powershell/module/microsoft.graph.devicemanagement.actions/new-mgdevicemanagementmobileapptroubleshootingeventapplogcollectionrequestdownloadurl](https://learn.microsoft.com/powershell/module/microsoft.graph.devicemanagement.actions/new-mgdevicemanagementmobileapptroubleshootingeventapplogcollectionrequestdownloadurl)

[https://learn.microsoft.com/graph/api/intune-devices-applogcollectionrequest-createdownloadurl?view=graph-rest-1.0](https://learn.microsoft.com/graph/api/intune-devices-applogcollectionrequest-createdownloadurl?view=graph-rest-1.0)























