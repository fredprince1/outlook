# outlook
Outlooks tips
File > Options > Calendar > Add Meeting Provider button under Calendar options > Uncheck Add online meeting...

Or

Set-OrganizationConfig -OnlineMeetingsByDefaultEnabled $false
Or

Set-MailboxCalendarConfiguration -Identity [user email] –OnlineMeetingsByDefaultEnabled $false
