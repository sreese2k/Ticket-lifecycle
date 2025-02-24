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
Today, we will walk through a hands-on lab in osTicket where we create, observe, and manage tickets as both an end-user and a help desk professional. This lab will demonstrate how tickets flow through the system, how we manage their properties, and how different roles interact with them. Additionally, we will make structural changes to our department hierarchy to optimize ticket management. We will create a new ticket to simulate a real world critical IT issue. The ticket will report that the entire mobile and online banking system is down a high-priority incident that requires immediate attention. When submitting this ticket, the system will capture essential details such as priority, department, SLA (Service Level Agreement), and agent assignment. This ensures that the issue is properly categorized and handled by the appropriate team.
</p>
<br />

<p>
<img src="https://imgur.com/26wKjIF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the ticket is created, we will log in as John, a Help Desk Agent, to observe and analyze the ticket’s properties in detail. As part of the Help Desk team, John’s initial responsibility is to review the ticket’s key attributes to determine its urgency, scope, and the appropriate course of action. The priority level of the ticket dictates the severity of the issue and the speed at which it must be addressed, ensuring that business-critical incidents are escalated appropriately. The department assignment specifies which team is responsible for resolving the issue, helping to streamline workflow efficiency by ensuring the ticket is handled by specialists in that area. Additionally, the SLA (Service Level Agreement) applied to the ticket establishes a clear expectation for response and resolution times, ensuring that deadlines are met and service quality is maintained. The assigned agent field indicates who is currently responsible for working on the ticket, providing transparency on workload distribution. Initially, John will be able to view the ticket details, including any notes or responses logged by the end-user. However, since the ticket might belong to another department, he may have restricted permissions when it comes to modifying or reassigning the ticket. This highlights the importance of structured access control within osTicket, ensuring that only authorized personnel can make critical changes while maintaining visibility for collaboration.
</p>
<br />

<p>
<img src="https://imgur.com/ABJdPYP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To properly categorize the issue, we will then update the ticket’s properties to ensure it receives the appropriate level of urgency and attention. Given that this is a business-critical outage affecting the entire mobile and online banking system, it requires immediate resolution to minimize disruption to customers and financial operations. We will assign it an SLA of Sev-A, which mandates a response time of one hour with 24/7 coverage, ensuring that support teams prioritize this issue regardless of the time of day. Additionally, we will reassign the ticket to the Online Banking Department, where specialized agents with expertise in banking infrastructure, transaction processing, and system recovery can handle the outage efficiently. This reassignment ensures that the ticket is in the hands of professionals equipped with the necessary tools and knowledge to diagnose the issue, coordinate with relevant IT and cybersecurity teams, and implement a rapid resolution strategy. Properly categorizing the ticket in this manner enhances accountability, streamlines the troubleshooting process, and helps prevent extended downtime that could negatively impact both the business and its customers.
</p>
<br />

<p>
<img src="https://imgur.com/txFUrVn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To complete the ticket resolution process, we will now switch to Jane, an agent from the appropriate department. Jane will take ownership of the ticket, investigate the outage, collaborate with the necessary teams, and document the resolution steps. Once the issue is fixed and verified, Jane will update the ticket status to Resolved and provide a closure note detailing the actions taken. This final step ensures that the end-user receives confirmation that the issue has been addressed, and the ticket is properly documented for future reference. This lab demonstrates how osTicket enables structured ticket management, ensuring that issues are properly logged, assigned, and resolved in a controlled environment. By following this workflow, we enhance the efficiency of IT support teams, improve response times, and maintain a well-organized help desk system. 
</p>
<br />

