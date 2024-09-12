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

Intake
- The first step will be to log in into our Virtual Machine created for osTickets. Copy the public IP address, open Remote Desktop, paste the IP address to log into it.
- Once you are there, open 2 tabs in the web browser. One will be to use osTickets as an Admin: http://localhost/osTicket/scp/login.php. And the other one will be to be an End User: http://localhost/osTicket
- We will start creating a ticket as an End user. Click on Open a New Ticket. Write down the contact information, remember that we are just practicing to get familiar with the tool, you can make up this data.
- Pick a Help Topic (Report a Problem). Issue summary: Entire mobile online banking system is down. Then in the Issue Sumary describe the issue, that would be what you see as a user, what others workers report, etc. Then click on Create Ticket.
  
Now we are going to see this ticket as the Admin person.
- Go to the other tab in your browser.
- As a Help Desk person, let's use John for this one, Sign in with the credentials already created.
- Click on the ticket and observe the ticket properties (Priority, Department, SLA, Assigned to).
 
Assignment and Communication
- Notice that you may change the properties of this ticket. Depending on the nature of the issue you can modify the severity. In this particular example we'll pick Sev-A and we'll type a short explanation like "this affects a lot of people", etc.
- You can also modify or correct the Help Topic. In this case the client picked "Report a problem" but this event would be more like "Report a problem/Business Critical Outage" and in the box, write a breve description.
- You may assign the ticket to individuals or to a Team and write any relevant note in the box or just a confirmation of the issue.
  
Working the Issue
- Log out as John and Log in as Jane. Once you see the Ticket click on it. Notice that it was assign to a team. In this case Jane can assign it to her self and type a  comment in the box  like "I will work on this ticket" ot any communication that help the process flow in case she is working with sobody else.
- In the Post Reply you may describe the course of action (things that you will do to restore the system).
- All the people in the Team will get an email for every update that is made.

  ![image](https://github.com/user-attachments/assets/ebeeaf39-ad5b-4f1d-a8ed-7e10d46c381b)

  
Resolution
- Once the problem is resolved, the last reply on the ticket should specify what happened, how it was solved, etc.
- Click on Status and set the ticket to "Resolved"


