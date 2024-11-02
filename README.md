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
In this project, we simulate helpdesk tickets and resolve them. Log in as an admin, navigate to Agents, then click on Departments. Select the Maintenance department, click More, and then choose Delete.

Go to http://localhost/osTicket and open a new ticket. Let's create a ticket about a user named Karen and is reporting that their company's mobile/online banking system is down.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/61ae6ef0-e982-4ba3-8588-da6b03129add" height="80%" width="80%" alt="user portal"/>
</p>
<p>

<img src="https://github.com/user-attachments/assets/eed67ceb-8e24-4e0a-bd92-a33c2b2c65f5" height="80%" width="80%" alt="ticket 1 created"/>
</p>
<p>We’ll access the ticket using the John Doe user from the Post-Installation project. Given the urgency of the online banking issue, we’ll set the SLA to "Sev-A." While John from the support team could handle it, it's better to assign it to the Online Banking team. Jane from that team will resolve and close the ticket.
</p>
<br />
<p>
<img src="https://github.com/user-attachments/assets/a7402634-c5b3-4934-8735-26a3fcf6da48" height="80%" width="80%" alt="john accessing ticket"/>
<img src="https://i.imgur.com/sKLV7cd.png" height="80%" width="80%" alt="jane closing ticket"/>
</p>

<p>
If a ticket indicates that the Adobe software update is broken in the accounting department, John should review the details. If the ticket lacks clarity, it’s best to call the customer to clarify the issue's scope and potential causes, such as a faulty patch or an Adobe-related problem.

In this scenario, let’s assume only a few users are affected. John can categorize it as "Sev-C" (minor impact), suggest that the users restart their computers, and close the ticket if that resolves the issue.

</p>
<img src="https://github.com/user-attachments/assets/30d6e70b-fb5c-4dab-acbb-c69bcb2c0950" height="80%" width="80%" alt="closed 2nd ticket"/>
<br />

<p>
For our final example, if the CFO can't turn on their laptop, it could be serious due to the need for critical documents. The severity will depend on how quickly the issue can be resolved (e.g., a battery problem is easier to fix than a failed inverter). We'll initially set the priority to "emergency" and adjust it later based on further information.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/200479b3-9c71-4b46-a0b9-e102b7be4522" height="80%" width"80%" alt="closed 3rd ticket"/>
</p>
<br />
<p>
After discovering that the charger was broken, we can set the SLA to "Sev-B," as it’s an easy fix. Once a new charger is obtained and the laptop powers on, we can close the ticket.
</p>

<p>
Resolving tickets requires some investigation, but asking the right questions and knowing when to escalate can make a significant impact.
</p>
