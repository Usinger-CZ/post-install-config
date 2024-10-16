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

I established a new role within osTicket, designated as "Supreme Admins," which confers comprehensive read and write access throughout the entire system.
</p>
<br />

![Screenshot (6)](https://github.com/user-attachments/assets/83a0990d-a804-49c0-9ef1-556645cbcb52)

I have onboarded two new agents into the system. Jane Doe has been appointed to the "Supreme Admin" role, which affords her comprehensive read and write access, whereas John Doe has been granted "Limited" access.
</p>
<br />

![Screenshot (13)](https://github.com/user-attachments/assets/fcaeb068-906a-4f69-ace5-0312a63cbf60) ![Screenshot (7)](https://github.com/user-attachments/assets/c7384421-afb8-4e28-a2a8-c814e4f7c72c)


Created a new department called SysAdmins and assigned Jane Doe, who was granted full access during the setup. John Doe was assigned to the default Support department. Additionally, a new team named "Online Banking" was created, with Jane Doe added to it. A second team, "Level 1 Support," was also created, and John Doe was assigned to this team.
</p>
<br />

![Screenshot (9)](https://github.com/user-attachments/assets/89c8ecf1-b445-4ccb-bc34-8c8b35d7bd52)


<p>
Created two new end users, Karen and Ken, for use in real-world simulations in the next lab.
</p>
<br />

![Screenshot (10)](https://github.com/user-attachments/assets/12c49844-ecc5-4157-8146-c74210c7ac09) ![Screenshot (11)](https://github.com/user-attachments/assets/026e9f69-2f6f-4bc2-ada1-f51ebe613918)




<p>
I developed three new Service Level Agreements (SLAs) with distinct levels of severity and escalation protocols. Severity Level A (Sev-A) is designed for 24/7 support, allowing for a mere one-hour grace period. Severity Level B (Sev-B) also provides 24/7 coverage but extends the grace period to four hours. In contrast, Severity Level C (Sev-C) is serviced exclusively during standard business hours, featuring an eight-hour grace period. 
</p>
<br />

![Screenshot (12)](https://github.com/user-attachments/assets/7389ff8c-1c64-44e0-b11f-ac57a89e5570)

<p>
Last I configured nine help topics for user ticket submissions, assigning each a corresponding priority level.
</p>
<br />
