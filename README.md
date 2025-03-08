<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/91f0c4c4-b78c-41ac-a185-30e0782d279c)

<p>
Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

</p>

<br />

![image](https://github.com/user-attachments/assets/833f2622-e361-4075-812d-e121388bc205)

<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

</p>
<br />

![image](https://github.com/user-attachments/assets/d2c5717c-463d-47a6-ab63-ce77cd974819)

<p>
Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

</p>
<br />

![image](https://github.com/user-attachments/assets/4516667c-04e8-4218-847b-1f8fd39a3878)

<p>Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)
</p>

![image](https://github.com/user-attachments/assets/2d7d9f9a-3211-41d6-9d14-0aeb5871b556)
<p>Configure Users (customers)
Agent Panel -> Users -> Add New
Karen
Ken
</p>
