---
Description: Per-user event generated by an email client that records when a contact is added, changed, or deleted in Parental Controls.
ms.assetid: 9d1f52ef-ff49-4c0d-a48a-93aeccbe7f2b
title: WPCEVENT_EMAIL_CONTACT event (Wpcevent.h)
ms.topic: reference
ms.date: 05/31/2018
---

# WPCEVENT\_EMAIL\_CONTACT event

Per-user event generated by an email client that records when a contact is added, changed, or deleted in Parental Controls.


```C++
const EVENT_DESCRIPTOR WPCEVENT_EMAIL_CONTACT = {0xe, 0x0, 0x10, 0x4, 0x16, 0xe, 0x8000000000000030};
```



## Parameters

<dl> <dt>

*AppName* 
</dt> <dd>

The name of the email application that is generating the event.

</dd> <dt>

*AppVersion* 
</dt> <dd>

The version of the email application that is generating the event.

</dd> <dt>

*OldName* 
</dt> <dd>

The previous email account name, if deleted or changed.

</dd> <dt>

*OldID* 
</dt> <dd>

The ID associated with the previous email account name.

</dd> <dt>

*NewName* 
</dt> <dd>

The new email account name, if added or changed.

</dd> <dt>

*NewID* 
</dt> <dd>

The ID associated with the new email account name.

</dd> <dt>

*Reason* 
</dt> <dd>

A value of the [**WPCFLAG\_ISBLOCKED**](/windows/win32/api/wpcevent/ne-wpcevent-wpcflag_isblocked) enumeration that indicates information about what events are blocked from use and what controls are in place.

</dd> <dt>

*EmailAccount* 
</dt> <dd>

The email account name for this user.

</dd> </dl>

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | None supported<br/>                                                             |
| Header<br/>                   | <dl> <dt>Wpcevent.h</dt> </dl> |



## See also

<dl> <dt>

[Using Logging APIs for Parental Controls](using-logging-apis-for-parental-controls.md)
</dt> <dt>

[**WPC\_ARGS\_CONVERSATIONINITEVENT**](/windows/win32/api/wpcevent/ne-wpcevent-wpc_args_conversationinitevent)
</dt> </dl>

 

 




