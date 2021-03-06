# Office 365 Groups activity reports

> **Important:** APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

You can gain insights into the activity of Office 365 Groups in your organization and see how many Office 365 groups are being created and used.

> **Note:** For details about different report views and names, see [Office 365 Reports - Office 365 groups](https://support.office.com/client/Office-365-groups-a27f1a99-3557-4f85-9560-a28e3d822a40).

## Reports

| Function                                 | Return Type | Description                              |
| :--------------------------------------- | :---------- | :--------------------------------------- |
| [Get user detail](../api/reportroot_getoffice365groupsactivityuserdetail.md) | Stream      | Get details about Office 365 Groups activity by user. |
| [Get activity counts](../api/reportroot_getoffice365groupsactivitycounts.md) | Stream      | Get the number of group activities across group workloads. |
| [Get group counts](../api/reportroot_getoffice365groupsactivitygroupcounts.md) | Stream      | Get the daily total number of groups and how many of them were active based on email conversations, Yammer posts, and SharePoint file activities.  |
| [Get storage](../api/reportroot_getoffice365groupsactivitystorage.md) | Stream      | Get the total storage used across all group mailboxes and group sites. |
| [Get file counts](../api/reportroot_getoffice365groupsactivityfilecounts.md) | Stream      | Get the total number of files and how many of them were active across all group sites associated with an Office 365 Group. |
