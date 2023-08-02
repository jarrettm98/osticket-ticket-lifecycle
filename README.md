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

<h2>Lifecycle Stages</h2>
<h3>Intake</h3>
First, go to the user ticket submission page through copy and pasting this link in the web address bar:

http://localhost/osTicket/

Using the information for the users created in the last tutorial, input an email and username. Next, add a Help Topic. There should be a drop down for a Summary and Description of the issue. This can be about anything that comes into mind. Create as many tickets as desired. It is recommended to create at least one severe ticket and a not so severe ticket. (For the section in the tutorial that will be assigning SLA to the tickets)

![osTicket Create Ticket](https://github.com/jarrettm98/osticket-ticket-lifecycle/assets/140662793/e7840d1f-14ba-4e88-ab19-4054edec0706)

<h3>Assignment and Communication</h3>

Copy and paste the following URL to log into the agent created in the previous tutorial that has system admin access:

  http://localhost/osTicket/scp/login.php

![osTickets Ticket Log](https://github.com/jarrettm98/osticket-ticket-lifecycle/assets/140662793/d3e4afaf-b322-4ea2-98dc-75cc9751efa4)

The agent should see all of the tickets submitted from the Intake Section of the tutorial. Click on one of the tickets. There will be options that can be adjusted. Status will show if the task is Open, closed, or resolved. Priority will show the urgency of the task. There are other options like Department and SLA. Use the ticket as a template and think about how this ticket should be categorized. If it is an urgent issue, set the Priority setting to High and the SLA to Sev-A. If the ticket needs to be assigned to another agent that may be a head of a team or department, assign it to them. Just know though that if the agent doesn't have access to the department in which the ticket is assigned, they won't see the ticket.

![osTicket Jane Assign](https://github.com/jarrettm98/osticket-ticket-lifecycle/assets/140662793/6d55b2e5-4baa-4cdc-aea5-22c8fbf9a72e)

<h3>Working the Issue</h3>

Towards the bottom of the ticket, there will be a text box as well as a "Ticket Status." These will be used to communicate to the user about the status of the situation. Pretend that the task has started and that the task was assigned to another agent. Assign the task to an agent. Type in the text box that the task is sent to the head of the department and leave the status as open. 

<h3>Resolution</h3>

Now, Pretend that the task at hand is resolved. Write in the box that the problem is fixed and change the status from "Open" to "Resolved."

Congrats! You now know how to send tickets as well as managing and resolving them.
