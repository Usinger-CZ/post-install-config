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

- Add new "ROLE" that has complete read/write access 
- Create two agents: one as a System Administrator and the other with "View Only" access
- Create a "Department" for organizing ticket assignment and configure "Teams" for assigning agents
- Create Users (customers) for simulated tickets in the next lab 
- Configure three new SLA's
- Create new "Help Topics" and assign appropriate Parent Topic's

<h2>Configuration Steps</h2>

![Config Roles](https://github.com/user-attachments/assets/a730daf9-d88c-4a4b-bec4-b2417b74ca03)

I created a new role in osTicket called "Supreme Admins," granting full read and write access to the entire system.
</p>
<br />

![Screenshot (6)](https://github.com/user-attachments/assets/83a0990d-a804-49c0-9ef1-556645cbcb52)

Added two new agents to the system. Jane Doe has been assigned the "Supreme Admins" role, providing her with full read and write access, as well as membership in the SysAdmins department. John Doe has been created with "View Only" access and assigned to the Support department.
</p>
<br />

![Screenshot (13)](https://github.com/user-attachments/assets/fcaeb068-906a-4f69-ace5-0312a63cbf60) ![Screenshot (7)](https://github.com/user-attachments/assets/c7384421-afb8-4e28-a2a8-c814e4f7c72c)


Created a new department called SysAdmins and assigned Jane Doe, who was granted full access during the setup. John Doe was assigned to the default Support department. Additionally, a new team named "Online Banking" was created, with Jane Doe added to it. A second team, "Level 1 Support," was also created, and John Doe was assigned to this team.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
