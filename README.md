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


<h2>Post Installation Setup</h2>

Configure Roles
 - Admin Panel -> Agents -> Roles

<img src="https://i.imgur.com/9fkjGRm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 
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

 - Swtich to Agent Panel -> Users -> Add New

   <img src="https://i.imgur.com/7hCvoSn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

 - Click Add User
    - Add Karen Doe as a user
    - Input email address
    - Click add user
    - Click user

- Click Add User
    - Add Ken Doe as a user
    - Input email address
    - Click add user

<p>
<img src="https://i.imgur.com/RT3fp9b.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA

 - Switch to Admin Panel -> Manage -> SLA


<img src="https://i.imgur.com/e7qV4MI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - Configure Sev-A for (1 hour, 24/7)
     - Click Add New SLA Plan
     - Insert SEV-A in name entry
     - Set 1 hour for grace period
     - Set 24/7 for Schedule
     - Click Add Plan

<img src="https://i.imgur.com/CTMk3jq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


 - Configure Sev-B (4 hours, 24/7)
   - Click Add New SLA Plan
     - Insert SEV-B in name entry
     - Set 4 hour for grace period
     - Set 24/7 for Schedule
     - Click Add Plan

<img src="https://i.imgur.com/Jzimwe8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


 - Configure Sev-C (8 hours, business hours)
   - Click Add New SLA Plan
     - Insert SEV-C in name entry
     - Set 8 hour for grace period
     - Set Monday - Friday 8am - 5pm with U.S. Holidays for Schedule
     - Click Add Plan
       
<img src="https://i.imgur.com/vtdAZVl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Configure Help Topics

 - Navigate to Admin Panel -> Manage -> Help Topics

 <img src="https://i.imgur.com/9fkjGRm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - Add Business Critical Outage Help Topic
    - Click Add New Help Topic
    - Type Business Critcial Outage in topic box
    - Click Save Changes

   <img src="https://i.imgur.com/I02DacW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   
 - Add Personal Computer Issues Help Topic
    - Click Add New Help Topic
    - Type Personal Computer Issues in topic box
    - Click Save Changes

  <img src="https://i.imgur.com/ZmHQPZG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
 - Add Equipment Request Help Topic
    - Click Add New Help Topic
    - Type Equipment Request Help in topic box
    - Click Save Changes
  
 <img src="https://i.imgur.com/2gbQ9Cs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
 
 - Add Password Reset Help Topic
    - Click Add New Help Topic
    - Type Password Reset Help in topic box
    - Click Save Changes
    - 
<img src="https://i.imgur.com/XLcrKjx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

