---
external help file: Microsoft.TeamsCmdlets.PowerShell.Custom.dll-Help.xml
Module Name: MicrosoftTeams
online version:
schema: 2.0.0
author: kenwith
ms.author: kenwith
ms.reviewer:
---

# New-TeamChannel

> [!IMPORTANT]
> The new OneDrive for Business Next Generation Sync Client lets you connect and sync files from your OneDrive for Business. You can add a work or school account to the new OneDrive for Business sync client and sync all your files in OneDrive to your computer.  For more information, see [Improve your OneDrive sync experience](https://go.microsoft.com/fwlink/p/?LinkId=717436).

## SYNOPSIS

Add a new channel to a team.

## SYNTAX

```
New-TeamChannel -GroupId <String> -DisplayName <String> [-Description <String>] [-MembershipType <String>] [-Owner <String>] [<CommonParameters>]
```

## DESCRIPTION

## EXAMPLES

### Example 1
```
New-TeamChannel -GroupId 126b90a5-e65a-4fef-98e3-d9b49f4acf12 -DisplayName "Architecture"
```
Create a standard channel with display name as "Architecture"

### Example 2
```
New-TeamChannel -GroupId 126b90a5-e65a-4fef-98e3-d9b49f4acf12 -DisplayName "Engineering" -MembershipType Private
```
Create a private channel with display name as "Engineering"

## PARAMETERS

### -GroupId
GroupId of the team

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -DisplayName
Channel display name.
Names must be 50 characters or less, and can't contain the characters # % & * { } / \ : \< \> ? + | ' "

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Description
Channel description.
Channel description can be up to 1024 characters.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -MembershipType (available in private preview)
Channel membership type, Standard or Private.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Owner (available in private preview)
UPN of owner that can be specified while creating a private channel.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS
### GroupId, DisplayName, Description, MembershipType, Owner

## OUTPUTS

### Id

## NOTES

## RELATED LINKS
