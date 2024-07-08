<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 (21H2)

## Ticket Lifecycle Stages

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

### Intake

1. Go to `localhost/osTicket/index.php` and click "Open a New Ticket" button to create a new ticket.

   <p align="center">
   <img src="https://i.imgur.com/psixsWn.png" height="80%" width="80%" alt="Open a New Ticket"/>
   </p>

2. Fill out the following fields:
   - Email address
   - Full name
   - Help topic (select from the drop-down menu)
   - Issue summary
   - Details in the box below
   - When finished, click "Create Ticket"

   <p align="center">
   <img src="https://i.imgur.com/Mnw3kNf.png" height="80%" width="80%" alt="Ticket Form"/>
   </p>

### Assignment and Communication

1. Login to osTicket portal as admin

   <p align="center">
   <img src="https://i.imgur.com/2Xu2Mtw.png" height="80%" width="80%" alt="Admin Login"/>
   </p>

2. Open your helpdesk ticket by clicking on the ticket number. From there you can:
   - Set the priority
   - Assign department
   - Assign to a specific rep
   - Set the service level agreement type (SLA)

   <p align="center">
   <img src="https://i.imgur.com/Gj2aawB.png" height="80%" width="80%" alt="Ticket Details"/>
   </p>

3. In the Tickets window, click "Assigned to" and use the drop-down menu to select a support rep.

   <p align="center">
   <img src="https://i.imgur.com/8KaX0Vx.png" height="80%" width="80%" alt="Assign Support Rep"/>
   </p>

4. Within the ticket tab, you can see the thread of any updates to the ticket and submit updates upon assignment. Once finished, click "Post Reply" and the ticket gets assigned to the appropriate department and your customer gets notified of the change.

   <p align="center">
   <img src="https://i.imgur.com/MNiXMEH.png" height="80%" width="80%" alt="Post Reply"/>
   </p>

### Working the Issue

1. Log into osTicket as an agent

   <p align="center">
   <img src="https://i.imgur.com/MdomY0W.png" height="80%" width="80%" alt="Agent Login"/>
   </p>

2. Once logged in, the Tickets window shows. It will show:
   - Ticket number
   - Last time it was updated
   - Subject
   - Who submitted the ticket
   - Level of priority
   - Who it is assigned to
   - Click on the ticket number to open the ticket to work.

   <p align="center">
   <img src="https://i.imgur.com/LMk1vFj.png" height="80%" width="80%" alt="Tickets Window"/>
   </p>

3. Once the ticket is opened, you can review all ticket items, the history of the ticket items, and the bottom section is where you can leave a reply for the user who submitted the ticket and an internal note to notify management if the ticket has been resolved.

   <p align="center">
   <img src="https://i.imgur.com/G9Vbbiy.png" height="80%" width="80%" alt="Ticket Details"/>
   </p>

4. In the post reply section, click the "Post Internal Note" tab, enter a summary in the Note Title box, type in the details in the body to comment on what has happened with this ticket.

   <p align="center">
   <img src="https://i.imgur.com/TXbfadF.png" height="80%" width="80%" alt="Post Internal Note"/>
   </p>

### Resolution

1. Click on the drop-down menu for Ticket Status, select "Closed", and click on "Post Note".

   <p align="center">
   <img src="https://i.imgur.com/JQTMQUd.png" height="80%" width="80%" alt="Close Ticket"/>
   </p>

2. osTicket will take you back to the Tickets tab. You will see a confirmation that the reply was posted successfully. Below the notification, the ticket no longer shows in the open menu.

   <p align="center">
   <img src="https://i.imgur.com/QnAgqBE.png" height="80%" width="80%" alt="Confirmation"/>
   </p>

3. To view the closed ticket:
   - Under the Tickets tab, click on "Closed"
   - Click on "today" from the drop-down menu
   - View the closed ticket by clicking on the ticket number in the closed ticket list

   <p align="center">
   <img src="https://i.imgur.com/hZVoZtW.png" height="80%" width="80%" alt="View Closed Ticket"/>
   </p>
