# <p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

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
<img src="https://imgur.com/etwaTTc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this lab, we explored the process of creating, managing, and resolving tickets within osTicket, both from the perspective of an end user and a help desk agent. This exercise helped us understand how tickets move through the system, how priorities are assigned, and how different roles interact with ticket properties.
</p>
<br />

<p>
<img src="https://imgur.com/dnjXnWq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, as an end user, we created a ticket with the issue involoing a entire online banking system being down. This simulated a real world critical outage that required immediate attention from the support team.
</p>
<br />

<p>
<img src="https://imgur.com/MrzLtjY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, as a Help Desk Agent (John), we accessed the ticket and observed its properties—including priority, department, SLA, and assigned agent. Since the issue was urgent, we updated the ticket’s priority to Sev A (1-hour response, 24/7) and assigned it to the Online Banking Department. After making these changes, we attempted to view or modify the ticket again as John, testing if permissions allowed further adjustments.
</p>
<br />

<p>
<img src="https://imgur.com/txFUrVn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Finally, as Jane (another agent), we took ownership of the ticket and worked it to completion. This involved responding to the end-user, troubleshooting the issue, and closing the ticket once the problem was resolved. This process demonstrated how osTicket allows teams to assign, track, and manage critical support issues efficiently while ensuring proper workflow and role based access control.
</p>
<br />
