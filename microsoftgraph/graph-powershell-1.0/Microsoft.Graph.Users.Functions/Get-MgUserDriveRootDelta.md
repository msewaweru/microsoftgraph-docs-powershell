---
external help file: Microsoft.Graph.Users.Functions-help.xml
Module Name: Microsoft.Graph.Users.Functions
online version: https://learn.microsoft.com/powershell/module/microsoft.graph.users.functions/get-mguserdriverootdelta
schema: 2.0.0
ms.subservice: sharepoint
---

# Get-MgUserDriveRootDelta

## SYNOPSIS
Track changes in a driveItem and its children over time.
Your app begins by calling delta without any parameters.The service starts enumerating the drive's hierarchy, returning pages of items and either an @odata.nextLink or an @odata.deltaLink, as described below.Your app should continue calling with the @odata.nextLink until you no longer see an @odata.nextLink returned, or you see a response with an empty set of changes.
After you have finished receiving all the changes, you may apply them to your local state.To check for changes in the future, call delta again with the @odata.deltaLink from the previous response.
Deleted items are returned with the deleted facet.Items with this property set should be removed from your local state.

> [!NOTE]
> To view the beta release of this cmdlet, view [Get-MgBetaUserDriveRootDelta](/powershell/module/Microsoft.Graph.Beta.Users.Functions/Get-MgBetaUserDriveRootDelta?view=graph-powershell-beta)

## SYNTAX

### Delta (Default)
```
Get-MgUserDriveRootDelta -DriveId <String> -UserId <String> [-ExpandProperty <String[]>] [-Filter <String>]
 [-Property <String[]>] [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>]
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-PageSize <Int32>] [-All]
 [-CountVariable <String>] [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

### Delta1
```
Get-MgUserDriveRootDelta -DriveId <String> -UserId <String> -Token <String> [-ExpandProperty <String[]>]
 [-Filter <String>] [-Property <String[]>] [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>]
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-PageSize <Int32>] [-All]
 [-CountVariable <String>] [-ProgressAction <ActionPreference>] [<CommonParameters>]
```

### DeltaViaIdentity1
```
Get-MgUserDriveRootDelta -InputObject <IUsersFunctionsIdentity> [-ExpandProperty <String[]>] [-Filter <String>]
 [-Property <String[]>] [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-Count]
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-ProgressAction <ActionPreference>]
 [<CommonParameters>]
```

### DeltaViaIdentity
```
Get-MgUserDriveRootDelta -InputObject <IUsersFunctionsIdentity> [-ExpandProperty <String[]>] [-Filter <String>]
 [-Property <String[]>] [-Search <String>] [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-Count]
 [-ResponseHeadersVariable <String>] [-Headers <IDictionary>] [-ProgressAction <ActionPreference>]
 [<CommonParameters>]
```

## DESCRIPTION
Track changes in a driveItem and its children over time.
Your app begins by calling delta without any parameters.The service starts enumerating the drive's hierarchy, returning pages of items and either an @odata.nextLink or an @odata.deltaLink, as described below.Your app should continue calling with the @odata.nextLink until you no longer see an @odata.nextLink returned, or you see a response with an empty set of changes.
After you have finished receiving all the changes, you may apply them to your local state.To check for changes in the future, call delta again with the @odata.deltaLink from the previous response.
Deleted items are returned with the deleted facet.Items with this property set should be removed from your local state.

## PARAMETERS

### -All
List all pages.

```yaml
Type: SwitchParameter
Parameter Sets: Delta, Delta1
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Count
Include count of items

```yaml
Type: SwitchParameter
Parameter Sets: DeltaViaIdentity1, DeltaViaIdentity
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -CountVariable
Specifies a count of the total number of items in a collection.
By default, this variable will be set in the global scope.

```yaml
Type: String
Parameter Sets: Delta, Delta1
Aliases: CV

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DriveId
The unique identifier of drive

```yaml
Type: String
Parameter Sets: Delta, Delta1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ExpandProperty
Expand related entities

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Expand

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Filter
Filter items by property values

```yaml
Type: String
Parameter Sets: (All)
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
Type: IUsersFunctionsIdentity
Parameter Sets: DeltaViaIdentity1, DeltaViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PageSize
Sets the page size of results.

```yaml
Type: Int32
Parameter Sets: Delta, Delta1
Aliases:

Required: False
Position: Named
Default value: 0
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

### -Property
Select properties to be returned

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Select

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

### -Search
Search items by search phrases

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Sort
Order items by property values

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: OrderBy

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Token
Usage: token='{token}'

```yaml
Type: String
Parameter Sets: Delta1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
Show only the first n items

```yaml
Type: Int32
Parameter Sets: (All)
Aliases: Limit

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
The unique identifier of user

```yaml
Type: String
Parameter Sets: Delta, Delta1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Skip
Skip the first n items

```yaml
Type: Int32
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IUsersFunctionsIdentity
### System.Collections.IDictionary
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphDriveItem
## NOTES
COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties.
For information on hash tables, run Get-Help about_Hash_Tables.

INPUTOBJECT `<IUsersFunctionsIdentity>`: Identity Parameter
  - `[CalendarId <String>]`: The unique identifier of calendar
  - `[ChatId <String>]`: The unique identifier of chat
  - `[ChatMessageId <String>]`: The unique identifier of chatMessage
  - `[ContactFolderId <String>]`: The unique identifier of contactFolder
  - `[ContactFolderId1 <String>]`: The unique identifier of contactFolder
  - `[ContentTypeId <String>]`: The unique identifier of contentType
  - `[DriveId <String>]`: The unique identifier of drive
  - `[DriveItemId <String>]`: The unique identifier of driveItem
  - `[EndDateTime <String>]`: Usage: endDateTime='{endDateTime}'
  - `[EventId <String>]`: The unique identifier of event
  - `[IncludePersonalNotebooks <Boolean?>]`: Usage: includePersonalNotebooks={includePersonalNotebooks}
  - `[Interval <String>]`: Usage: interval='{interval}'
  - `[ListItemId <String>]`: The unique identifier of listItem
  - `[MailFolderId <String>]`: The unique identifier of mailFolder
  - `[MailFolderId1 <String>]`: The unique identifier of mailFolder
  - `[OnenotePageId <String>]`: The unique identifier of onenotePage
  - `[OnlineMeetingId <String>]`: The unique identifier of onlineMeeting
  - `[Q <String>]`: Usage: q='{q}'
  - `[Skip <Int32?>]`: Usage: skip={skip}
  - `[StartDateTime <String>]`: Usage: startDateTime='{startDateTime}'
  - `[TimeZoneStandard <String>]`: Usage: TimeZoneStandard='{TimeZoneStandard}'
  - `[TodoTaskListId <String>]`: The unique identifier of todoTaskList
  - `[Token <String>]`: Usage: token='{token}'
  - `[Top <Int32?>]`: Usage: top={top}
  - `[User <String>]`: Usage: User='{User}'
  - `[UserId <String>]`: The unique identifier of user

## RELATED LINKS

[https://learn.microsoft.com/powershell/module/microsoft.graph.users.functions/get-mguserdriverootdelta](https://learn.microsoft.com/powershell/module/microsoft.graph.users.functions/get-mguserdriverootdelta)

[https://learn.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0](https://learn.microsoft.com/graph/api/driveitem-delta?view=graph-rest-1.0)
























