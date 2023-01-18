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

<h2>Configuration Steps</h2>

Configure Roles
  - Admin Panel -> Agents -> Roles
  - Supreme Admin

<p>
<img src="https://i.imgur.com/BmgJh4a.png" height="40%" width="40%" alt="X"/>
</p>

Configure Departments
  - Admin Panel -> Agents -> Departments
  - System Administrators

<p>
<img src="https://i.imgur.com/okRF9jy.png" height="40%" width="40%" alt="X"/>
</p>

Configure Teams
  - Admin Panel -> Agents -> Teams\
    - Level I Support
    - Level II Support

<p>
<img src="https://i.imgur.com/rHvZ1uN.png" height="40%" width="40%" alt="X"/>
</p>

Allow anyone to create tickets
  - Admin Panel -> Settings -> User Settings
  - Registration Required: Require registration and login to create tickets (leave unchecked) 

<p>
<img src="https://i.imgur.com/CeYalJI.png" height="40%" width="40%" alt="X"/>
</p>

Configure Agents (workers)
  - Admin Panel -> Agents -> Add New
    - Jane
    - John

<p>
<img src="https://i.imgur.com/IqTEZIw.png" height="40%" width="40%" alt="X"/>
</p>

Configure Users (customers)
  - Agent Panel -> Users -> Add New
      - Karen
      - Ken

<p>
<img src="https://i.imgur.com/gFAmlC1.png" height="40%" width="40%" alt="X"/>
</p>

Configure SLA
  - Admin Panel -> Manage -> SLA
     -  Sev-A (1 hour, 24/7)
     -  Sev-B (4 hours, 24/7)
     -  Sev-C (8 hours, business hours)

<p>
<img src="https://i.imgur.com/uunBXn8.png" height="40%" width="40%" alt="X"/>
</p>

Configure Help Topics
  - Admin Panel -> Manage -> Help Topics
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset

<p>
<img src="https://i.imgur.com/GBrmNUp.png" height="40%" width="40%" alt="X"/>
</p>


