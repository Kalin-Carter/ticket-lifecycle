<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an end-user, create the following ticket
entire mobile/online banking system is down
As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To
Set Properties to the ticket
Sev-A (1 hour, 24/7)
Online Banking Department
Attempt to observe the ticket again as “john”. Can you view or change?
Work the ticket to completion as jane
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an end-user, create the following ticket
accounting department needs adobe upgrade, broken
As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To
Set Properties to the ticket
Sev-B (4 hours, 24/7)
Support
Work the ticket to completion as john

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an end-user, create the following ticket
CFO’s laptop will no longer turn on

As a Help Desk Agent (john), observe the ticket’s properties
	Priority
	Department
	SLA
	Assigned To
Set Properties to the ticket
Sev-B (4 hours, 24/7)
Support
Work the ticket to completion as john

</p>
<br /># ticket-lifecycle
Assign Properties to All Tickets
Set all tickets to SLA: SEV-A.
Assign departments accordingly (make SysAdmins the last one).
Observe that the SysAdmins ticket becomes inaccessible from the Agent Panel if you’re not assigned or lack permissions.
Regain AccessGo to the Admin Panel → Agents → Departments.
Assign yourself view access to the SysAdmins department.
Switch back to the Agent Panel – now the escalated SysAdmins ticket is visible, but note:
You can view the ticket.
You cannot make changes unless you have explicit edit permissions or are assigned to it.
Resolve All Tickets
Go through and close/resolve each one.
Tip: In most ticketing systems (likely including this one), there’s an email notification system:
Every time you update a ticket, the user gets an email.
If they reply to that email, it logs a response in the ticket automatically.


