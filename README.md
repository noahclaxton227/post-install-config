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

- Item 1: Configure Roles, Departments, and Teams
- Item 2: Configure Agents 
- Item 3: Configure Users 
- Item 4: SLA Configuration
- Item 5: Help Topic Configuration 

<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/noahclaxton227/post-install-config/assets/150629711/bba74187-6e60-4dbc-81f9-639f5f858e58)
</p>
<p>
In this section, multiple new roles were created using osTicket. These roles refer to the permissions assigned to groups of users. For example, "Supreme Admin" roles will be able to manage all accounts while users may only be able to create tickets. Both teams (grouping of employees set to tackle specific issues) and departments (for example, maintenance or support) were also created to ensure tasks go to the correct people. 
</p>
<br />
<p>
  
![image](https://github.com/noahclaxton227/post-install-config/assets/150629711/ef02294a-15b7-4c25-af5d-b5f20394ee37)

</p>
<p>
Multiple agents were added in order to simulate the employees using the site. In this case, Jane is a part of the Systems Admin department while John is part of the Support department. These departments are crucial to workflow as each may handle different issues, have different SLA's, or even email templates. 
</p>
<br />
<p>
  
![image](https://github.com/noahclaxton227/post-install-config/assets/150629711/1a5d0f10-5c49-4be5-be87-e7f0bc19205c)

</p>
<p>
In order to simulate the creation of tickets, we need users. To construct them, the process is almost identical to that of Agents, however we must be on the Agent Panel, rather than Admin. To make a ticket, all these users must do is input their name, email, help topic, and issue summary. If their "user name" is in this system, the ticket will go to the correct departmet.
</p>
<br />
<p>
  
![image](https://github.com/noahclaxton227/post-install-config/assets/150629711/d63d9b6d-32e1-437c-a490-1ef9f61bb7d9)

</p>
<p>
Service Level Agreements (SLA) are a must-have in a IT Support setting, as they define the response times a customer can expect when a problem arises. For example, in this lab a Sev-A problem is of critical importance and the goal is for the problem to be solved within 1 hour (within reason).
</p>
<br />
<p>
  
![image](https://github.com/noahclaxton227/post-install-config/assets/150629711/9949e0e0-5c1b-4d85-92b8-cc5e590c3288)

</p>
<p>
A help topic is simply the general subject the issue would fall into. Just as school has math, english, and science, help topics have subjects like access issues, general inquiry, or password reset. This both categortizes the specifc issue, and helps the IT Department route/assign the issue to the correct people. 
</p>
<br />
