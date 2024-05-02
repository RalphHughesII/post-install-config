<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Post Installation Setup</h2>

Configure Roles
 - Admin Panel -> Agents -> Roles


<img src="https://i.imgur.com/ZaAeyyM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - Click add new role and input a name (Example: Supreme Admin).  

 - Select Permissions and enable all available permissions for Tickets, Tasks, and Knowledgebase

<img src="https://i.imgur.com/xRXrTA2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Configure Departments
 - Admin Panel -> Agents -> Departments
 
 <img src="https://i.imgur.com/lEUaRbw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  - Click "Add New Department"
        - Type System Administrators in the Name box

Configure Teams
 - Admin Panel -> Agents -> Teams

<img src="https://i.imgur.com/I1tu83I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 - Click on Add New Team.  Name it Level II Support and click create team

Allow anyone to create tickets
 - Navigate to Admin Panel -> Settings -> User Settings.
 - Make sure require registration and login to create tickets is unchecked

<img src="https://i.imgur.com/1zN6CnN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Configure Agents (workers)
 - Navigate to Admin Panel -> Agents -> Add New

<img src="https://i.imgur.com/I4shSGX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 
- Add Jane doe as a user
  
   - Input name and email address
   - Create a username and password (uncheck change password at login)
      - Open the access tab.
         - Assign her in system administrators department
         - Assign her Supreme Admin role
       - Open the Teams tab
          - Assign her to level II support
       - Click create
  
 - Add John doe as a user

      - Input name and email address
      - Create a username and password (uncheck change password at login)
      - Open the access tab.
         - Assign him in the support department
         - Assign him view only role
       - Click create

Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken





<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
