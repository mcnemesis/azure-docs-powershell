---
external help file: Microsoft.WindowsAzure.Commands.ServiceManagement.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: 580B3B9F-FD85-4531-8586-F25A182E7FB2
---

# Get-AzureLocation

## SYNOPSIS
Gets the available data center locations for the current Azure subscription.

## SYNTAX

```
Get-AzureLocation [-Profile <AzureSMProfile>] [-InformationAction <ActionPreference>]
 [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
powershell_prelim

The **Get-AzureLocation** cmdlet returns a list object with the available Azure data centers and their properties for the current Azure subscription.
Before you run this cmdlet, you need to set your current subscription with **Select-AzureSubscription** and **Set-AzureSubscription**.

## EXAMPLES

### Example 1
```
C:\PS> Get-AzureLocation
```

This command gets a list of available data centers, and their properties, for the current subscription.

## PARAMETERS

### -Profile
Specifies the Azure profile from which this cmdlet reads. If you do not specify a profile, this cmdlet reads from the local default profile.

```yaml
Type: AzureSMProfile
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationAction
Specifies how this cmdlet responds to an information event.

The acceptable values for this parameter are:

- Continue
- Ignore
- Inquire
- SilentlyContinue
- Stop
- Suspend

```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
Specifies an information variable.

```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS


