<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h1>Post-Install Configuration</h1>

With all components of the osTicket System installed, the next step is to take osTicket into its operational stage, allowing for it to handle tickets, end-user requests and support staff assignments.

<h2>Configuration Steps</h2>

<p>
-  Roles: Assign roles to different agents (Admins and Support Staff) to manage access and permissions
-  Departments: Create various departments (e.g., IT, Customer Support) to handle tickets based on the various requests
-  Teams: Configure teams to handle specific types of support, such as Level I or Level II Support
-  Agents (or Workers): Add agents who will manage and resolve the tickets
-  Users (i.e., Customers): Add the users who will submit tickets to the help desk
-  SLA's (Service Level Agreements): Configure SLA's to ensure timely ticket resolutions based on severity
-  Help Desk Topics: Define help topics to categorize tickets based on the issues users may encounter
</p>
<br />

<h1>Outline</h1>

-  Configure Roles
   -  Admin Panel -> Agents -> Roles
   -  Assign the "Supreme Admin" role for full Control

-  Configure Departments
    -  Admin Panel -> Agents -> Departments
    -  Create "System Administrators" department to handle high-priority issues and assignments.

![421120905-1ab71a76-b08a-4b49-adf1-da37f151c151](https://github.com/user-attachments/assets/c8b7dfb9-2dfb-49c8-a311-64a130afac0f)


  -  Configure Teams
     -  Admin Panel -> Agents -> Teams
     -  Set up Level I and Level II support teams to handle different tiers of support requests

  -  Configure Agents
     -  Admin Panel -> Agents -> Add New
     -  Add agents to handle oncoming tickets from end-users. For example, we will add `Jane` and `John` as Agents.
   
![421121070-7ab81c7c-c35b-46c4-bcac-5003a7d96348](https://github.com/user-attachments/assets/be234317-0ddf-4282-878b-2fab96f93623)


  -  Configure End-Users (Clients)
      -  Agent Panel -> Users -> Add New
      -  `Karen` and `Ken` who will serve as end-users to submit tickets for consideration.
   
![421121298-dace0c6b-9473-4b81-ad8d-86a614bd4218](https://github.com/user-attachments/assets/69a17245-7149-4b9b-bea2-cffaff891c8e)


  -  Configure SLAs (Service Level Agreements)

Service Level Agreements define the timeframes in which tickets are to be solved based on a number of factors, namely involving urgency and the date the ticket was received into the system. Proper monitoring and configuration of SLAs will ensure critical issues are prioritized and handled in an efficient manner



![421121412-6e35c262-d9d4-4b14-b88c-e2a7a4210766](https://github.com/user-attachments/assets/cf3c8485-4d97-428d-af7a-59e983fdf1ac)


  1.  Admin Panel -> Manage -> SLA
  2.  Set up the following SLAs:
      - Sev-A: 1 hour, 24/7 coverage for critical system outages
      - Sev-B: 4 hours, 24/7 coverage for high-priority issues such as software failures
      - Sev-C: 8 hours, business hours coverage for less critical issues, such as system lockouts and password                      resetting.
    
  3.  Configure Help Topics
     -  Help topics categorize the level of support end-users may submit. Proper categorization leads to proper ticket routing, meaning tickets will be received and addressed within a reasonable timeframe.


      
![421121513-f9495391-22e3-47d8-af88-5c43d20bc636](https://github.com/user-attachments/assets/99eee362-904b-4ec6-bd37-4ad9491d1f14)


  1. Admin Panel -> Manage -> Help Topics
  2. Add common help topics such as:
       -  Business Critical Outage
       -  Personal Computer Issues
       -  Equipment Request
       -  Password Reset
    


