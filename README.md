<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1 manage OsTicket help topics
- Item 2 configure SLA's
- Item 3 change or reset agent password

<h2>Configuration Steps</h2>

<p>
![Image Alt](https://github.com/TracyBartholomew/Osticket-post-installation/blob/b94c8da0451feb5108f1998c16ade38185a1bfe1/IMG_0366.jpeg)
</p>
<p>
•	To add a new help topic, click the Add New Topic button.
•	Enter the Topic Name, and provide a Description if necessary.
•	You can configure specific settings like auto-assigning tickets, setting department routes, or adding custom forms to gather more information.
•	To edit an existing help topic, click on the topic’s name and make the necessary adjustments.
•	Use the Sorting feature to arrange the topics in an order that makes sense for your users.
*  You can also enable or disable topics depending on your current needs.
•	When done, click Save Changes to finalize your settings.

These steps will help you efficiently manage and customize your help desk topics in osTicket.
</p>
<br />
![Image Alt](https://github.com/TracyBartholomew/Osticket-post-installation/blob/e18c5ac62723450fec83d0760654e2d688fef99d/IMG_0365.jpeg)
<p>
!
</p>
<p>
•	In the Admin Panel, go to Manage > SLA Plans. 
•	This section allows you to view, create, and manage the different SLA plans for your tickets.
•	To add a new SLA plan, click the Add New SLA button.
•	Enter the Name of the SLA plan (“High Priority”, “Standard Response”).
•	Define the Response Time within 24 hours, 4 hours, etc.) and set the plan to apply during Business Hours or 24/7.
•	To edit an existing SLA plan, click on its name and adjust the settings as needed.

<p>
![Image Alt](https://github.com/TracyBartholomew/Osticket-post-installation/blob/dd8faf8b8cc7499b970bb4b48d7a448108b21814/IMG_0364.jpeg)
</p>
•	Log in to your osTicket admin account.
•	Navigate to the Admin Panel by clicking the gear icon in the top-right corner of the dashboard.
* Navigate to Agents
•	In the Admin Panel, go to Agents > Agents.
•	Find the agent whose password you want to change and click on their name to open their profile.
* Change the Password
•	In the agent’s profile, scroll down to the Account Access section.
•	Enter the new password in the New Password and Confirm New Password fields.
•	Click Save Changes to update the agent’s password.

The agent can now log in using their new password.
