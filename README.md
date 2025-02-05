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

- Configure Roles(for Grouping Permissions)
- Configure Departments and Teams(Ticket Visibility, Help Desk vs SysAdmins, vs Networking &
  Teams You Pull Agents From Different Departments)
- Configure Agents and Users(Workers and Customers)
- Configure SLA and Help Topics(Help Topics is for when users create a ticket)


<h2>Configuration Steps</h2>


![image](https://github.com/user-attachments/assets/36fea159-72be-4654-8a52-98024576e4cb)

<p>
To configure Roles you first go to the Admin panel and then you go to Agents. Next you click Roles then within Roles you choose any role or you can create your own role by clicking the ADD New Role tab and when creating your new role you choose the permissions the role can have by checking the boxes in the Tickets, Tasks, Knowledgebase tabs. 
</p>
<br />

![image](https://github.com/user-attachments/assets/7112d493-a97a-47d2-a1ae-0e0bf515f98c)
![image](https://github.com/user-attachments/assets/7d6070b0-1b1b-43b6-80f8-4954dd74a796)


<p>
To configure the Department, within the Agent tab you click Departments and within that you can add and new department by clicking Add New Department and configure it to your liking. And for Teams, from the Agent tab and then you got to Teams within Teams you can create and New Team. 
<br />

![image](https://github.com/user-attachments/assets/1d573f5b-f802-4f51-b94d-65a850240c46)
![image](https://github.com/user-attachments/assets/d5b5dcb9-e253-430d-b1b1-30f7b0fff6a3)


<p>
To configure the Agents, within the Agent tab you click Add New Agent a you fill in the agents information. Then you can choose what the agent can do within the Acess, Permissons, Teams tab.
To configure the Users you just to the go to he Users tab within Agents and just click Add Users and fill in the users information.
<br />

![image](https://github.com/user-attachments/assets/81a45079-27a7-4fb7-a3f3-d571af3480ff)
![image](https://github.com/user-attachments/assets/176c7e49-302b-4ff6-802f-29bab78746e1)
<p>To configure SLA you within the Admin Panel then go to Manage and click SLA and then you click Add New SLA Plan to create your SLA. To configure Help Topics within the Admin Panel you go to Manage and click Help Topics and within that you can create help topics by clicking Add New Help Topics.
<br />




