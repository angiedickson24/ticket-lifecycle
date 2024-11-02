<p align="center">
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

<h2>Working through Tickets</h2>

<p>
In this project, we simulate some helpdesk tickets and work through them to resolution. Login as an admin, find agents and click on departments. Check the Maintenance department, click More then delete. 

Go to http://localhost/osTicket and open a new ticket. Let's create a ticket about a user named Karen and is reporting that their company's mobile/online banking system is down.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/61ae6ef0-e982-4ba3-8588-da6b03129add" height="80%" width="80%" alt="user portal"/>
</p>
<p>

<img src="https://github.com/user-attachments/assets/eed67ceb-8e24-4e0a-bd92-a33c2b2c65f5" height="80%" width="80%" alt="ticket 1 created"/>
</p>
<p>We’ll access this ticket using the John Doe user we created in the Post-Installation project. Since online banking being down is urgent, we’ll set the SLA to "Sev-A." Although John is on the support team and could work on it, it's more appropriate to assign it to the Online Banking team. Jane from that team can then resolve and close the ticket.
</p>
<br />
<p>
<img src="https://github.com/user-attachments/assets/a7402634-c5b3-4934-8735-26a3fcf6da48" height="80%" width="80%" alt="john accessing ticket"/>
<img src="https://i.imgur.com/sKLV7cd.png" height="80%" width="80%" alt="jane closing ticket"/>
</p>

<p>
If a ticket is submitted saying the Adobe software update is broken in the accounting department, and John picks it up, he should check for details. If the ticket is unclear, it’s best to call the customer to clarify the scope of the issue and possible causes, like whether it's a faulty patch or an Adobe issue.

In this example, let's say only a few users are affected. John can classify it as a "Sev-C" (minor impact), advise the users to try restarting their computers, and, if that solves the problem, close the ticket.

</p>
<img src="https://github.com/user-attachments/assets/30d6e70b-fb5c-4dab-acbb-c69bcb2c0950" height="80%" width="80%" alt="closed 2nd ticket"/>
<br />

<p>
For a final example, if the CFO can’t turn on their laptop, this is potentially serious since they may need critical documents. However, the severity depends on how quickly it can be fixed (e.g., a battery issue is easier than a failed inverter). We’ll set the priority to "emergency" for now and adjust it if needed once we have more details..
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/200479b3-9c71-4b46-a0b9-e102b7be4522" height="80%" width"80%" alt="closed 3rd ticket"/>
</p>
<br />
<p>
After learning the charger was broken, we can set the SLA to "Sev-B" since it's an easy fix. Once a new charger is found and the laptop powers on, we can close the ticket.
  
</p>

<p>
Working through tickets requires some investigation, but asking the right questions and knowing when to escalate makes a big difference.
</p>
