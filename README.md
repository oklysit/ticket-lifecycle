<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>

<p>

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. 
You will create and interact with sample tickets as both an End User and Helpdesk Worker in order to observe the lifecycle of a ticket within a ticketing system. 
Ideally, sample information has been created during the [Post-Install Configuration](https://github.com/oklysit/post-install-config/).

</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>

Intake 
> - Go to End User site located at: http://localhost/osTicket/
> - Create a New Ticket
> - Enter End User info 
> - Choose a Helpdesk Topic
> - Attach files if desired (optional)
> - Create Ticket

Assignment and Communication
> - Browse to help desk login page located at: http://localhost/osTicket/scp/login.php
> - Log in with User (Worker) created during [Post-Install Configuration](https://github.com/oklysit/post-install-config/)
> - Observe Tickets in dashboard
> - Click on sample ticket created in prior Intake step
> - Change Priority to observe changes
> - Change SLA and choose sample SLA created during [Post-Install Configuration](https://github.com/oklysit/post-install-config/) to observe changes
> - Assign to another Helpdesk staff created during [Post-Install Configuration](https://github.com/oklysit/post-install-config/)

Working the Issue
> - Log in as a different helpdesk User assigned a task in prior step
> - Post reply as if you were interacting with sample issue
> - Create or add attachments if desired
> - Observe the updates posted to the ticket when changes are made

Resolution
> - Log in as helpdesk user with appropriate permissions to close tickets
> - Change tickets status to "Closed" and Post Reply
> - Observe ticket having moved to "Closed" tab on dashboard

</p>
