---
external help file:
Module Name: Microsoft.Graph.Users.Functions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.functions/get-mgusercalendareventdelta
schema: 2.0.0
---

# Get-MgUserCalendarEventDelta

## SYNOPSIS
Invoke function delta

## SYNTAX

### Delta2 (Default)
```
Get-MgUserCalendarEventDelta -UserId <String> [<CommonParameters>]
```

### Delta3
```
Get-MgUserCalendarEventDelta -CalendarId <String> -UserId <String> [<CommonParameters>]
```

### DeltaViaIdentity2
```
Get-MgUserCalendarEventDelta -InputObject <IUsersFunctionsIdentity> [<CommonParameters>]
```

### DeltaViaIdentity3
```
Get-MgUserCalendarEventDelta -InputObject <IUsersFunctionsIdentity> [<CommonParameters>]
```

## DESCRIPTION
Invoke function delta

## EXAMPLES

### Example 1: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

### Example 2: {{ Add title here }}
```powershell
PS C:\> {{ Add code here }}

{{ Add output here }}
```

{{ Add description here }}

## PARAMETERS

### -CalendarId
key: id of calendar

```yaml
Type: System.String
Parameter Sets: Delta3
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: Microsoft.Graph.PowerShell.Models.IUsersFunctionsIdentity
Parameter Sets: DeltaViaIdentity2, DeltaViaIdentity3
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -UserId
key: id of user

```yaml
Type: System.String
Parameter Sets: Delta2, Delta3
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IUsersFunctionsIdentity

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphEvent1

## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


INPUTOBJECT <IUsersFunctionsIdentity>: Identity Parameter
  - `[CalendarId <String>]`: key: id of calendar
  - `[ContactFolderId <String>]`: key: id of contactFolder
  - `[EndDateTime <String>]`: 
  - `[EventId <String>]`: key: id of event
  - `[IncludePersonalNotebooks <Boolean?>]`: 
  - `[MailFolderId <String>]`: key: id of mailFolder
  - `[ManagedDeviceId <String>]`: key: id of managedDevice
  - `[OnenotePageId <String>]`: key: id of onenotePage
  - `[RoomList <String>]`: 
  - `[Skip <Int32?>]`: 
  - `[StartDateTime <String>]`: 
  - `[TimeZoneStandard <String>]`: 
  - `[Top <Int32?>]`: 
  - `[User <String>]`: 
  - `[UserId <String>]`: key: id of user

## RELATED LINKS

