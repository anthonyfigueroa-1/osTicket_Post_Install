<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Post Install</h1>
This tutorial outlines the post installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Prerequisites<h2>

- Have followed and completed the steps to [install osTicket](https://github.com/anthonyfigueroa-1/osTicket_Installation).

<h2>Steps</h2>

<p>
<img src="https://i.imgur.com/PumkA6v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/YJV0et2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Configure Roles
    - Admin Panel -> Agents -> Roles
    - Supreme Admin
    - Give access to do anything
  
<br />

  <p>
<img src="https://i.imgur.com/gjCc6I5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Configure Departments
    - Admin Panel -> Agents -> Departments
    - System Administrators
  
<br />
  
  <p>
<img src="https://i.imgur.com/aAnNnkh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Configure Teams
    - Admin Panel -> Agents -> Teams
      - Level I Support
      - Level II Support
  
<br />
  
  <p>
<img src="https://i.imgur.com/MYQAeU1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Allow anyone to create tickets
    - Admin Panel -> Settings -> User Settings
    - Registration Required: Require registration and login to create tickets, make sure it's unchecked
  
<br />
  
  <p>
<img src="https://i.imgur.com/nn5k9Jv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
   <p>
<img src="https://i.imgur.com/vozAy4o.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
   <p>
<img src="https://i.imgur.com/J0p3FQM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
   <p>
<img src="https://i.imgur.com/ibpwr4J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Configure Agents (workers)
    - Admin Panel -> Agents -> Add New
      - Jane
      - John
  
<br />
  
  <p>
<img src="https://i.imgur.com/9Aj1Rmr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
    <p>
<img src="https://i.imgur.com/OwZmkC8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Configure Users (customers)
    - Agent Panel -> Users -> Add New
      - Karen
      - Ken

<br />
  
  <p>
<img src="https://i.imgur.com/kM581Qe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Configure SLA
    - Admin Panel -> Manage -> SLA
      - Sev-A (1 hour, 24/7)
      - Sev-B (4 hours, 24/7)
      - Sev-C (8 hours, business hours)
  
<br />
  
  <p>
<img src="https://i.imgur.com/Vxm9LXG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
  
  - Configure Help Topics
    - Admin Panel -> Manage -> Help Topics
      - Business Critical Outage
      - Personal Computer Issues
      - Equipment Request
      - Password Reset
  
<br />
