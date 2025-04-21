<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) [ Coming Soon! ]

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

1. **Rename the osTicket Installation Directory**  
   - Change the default `/upload` directory to something more secure (e.g., `/support`) for security and branding purposes.

2. **Configure Email Settings**  
   - Set up SMTP for outgoing mail and enable IMAP/POP3 for incoming ticket generation via email.

3. **Create and Configure Departments, Teams, and Help Topics**  
   - Organize support workflow by creating relevant departments (e.g., IT, HR), assigning teams, and setting up common help topics.

4. **Set Up User Roles and Permissions**  
   - Define agent roles with appropriate access levels and permissions to manage tickets and internal notes.

5. **Enable and Customize Auto-Responder and System Alerts**  
   - Configure auto-reply messages for new tickets and system alerts for ticket updates, assignments, and overdue notices.

