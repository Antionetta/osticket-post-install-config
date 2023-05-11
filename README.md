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

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/hKht968.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Roles</h3>
Admin Panel -> Agents -> Roles

- System Admin

</p>
<br />

<p>
<img src="https://i.imgur.com/xoFvDSW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Departments</h3>
Admin Panel -> Agents -> Departments

- System Administrators

</p>
<br />

<p>
<img src="https://i.imgur.com/bkZ5W7t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Teams</h3>
Admin Panel -> Agents -> Teams

- Level I Support
- Level II Support

</p>
<br />

<p>
<img src="https://i.imgur.com/xGSMFua.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Allow anyone to create tickets</h3>
Admin Panel -> Settings -> User Settings

- Registration Required: Require registration and login to create tickets 


</p>
<br />


<p>
<img src="https://i.imgur.com/EbSUdTK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Agents (workers)</h3>
Admin Panel -> Agents -> Add New

- John


</p>
<br />

<p>
<img src="https://i.imgur.com/CxLNLKq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Users (customers)</h3>
Agent Panel -> Users -> Add New

-Barbie


</p>
<br />

<p>
<img src="https://i.imgur.com/C8O0dJz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure SLA</h3>
Admin Panel -> Manage -> SLA

- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, business hours)


</p>
<br />

<p>
<img src="https://i.imgur.com/b8PIa57.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<h3>Configure Help Topics</h3>
Admin Panel -> Manage -> Help Topics

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset



</p>
