![7](https://github.com/user-attachments/assets/3bb73ad3-7b0c-48f0-a1ac-84ff73ce1082)<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Acknowledge Agent Panel vs Admin Panel
- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<h3>Configure Roles (for grouping permissions)</h3>
<p>Admin Panel -> Agents -> Roles</p>
<p>Supreme Admin</p>

![1](https://github.com/user-attachments/assets/f6a5e99b-ed70-43e1-9220-0ee137518cfe)

![2](https://github.com/user-attachments/assets/69b1a88c-af22-4602-9c79-d76427dfd9a5)

![3](https://github.com/user-attachments/assets/d0d4b8e7-f001-4589-8051-aaadcf2bf9f9)

![4](https://github.com/user-attachments/assets/92297cde-f453-46c7-b8cc-660975357a17)

![5](https://github.com/user-attachments/assets/72bdd16d-435a-4d51-b419-9dcd0062bd49)

<h3>Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)</h3>
<p>Admin Panel -> Agents -> Departments</p>

![6](https://github.com/user-attachments/assets/949cf8e2-1354-4200-8165-f04f765ca549)

![7](https://github.com/user-attachments/assets/d310ddab-c42e-40c8-9edb-d36004142f78)

<h3>Configure Teams</h3>
<p>Admin Panel -> Agents -> Teams (Pull Agents from different Departments)</p>

![8](https://github.com/user-attachments/assets/f29d9f13-c9af-422d-9281-fdc326d3ca18)

![9](https://github.com/user-attachments/assets/860f4e5f-dd8d-4cb7-bc79-fd38a3703123)

<h3>Allow anyone to create tickets</h3>
<p>Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)</p>

![10](https://github.com/user-attachments/assets/dcf4bba6-f1ea-4d3a-b9dc-7fa55afc9868)

<h3>Configure Agents (workers)</h3>
<p>Admin Panel -> Agents -> Add New</p>

![11](https://github.com/user-attachments/assets/38d188b3-dc1a-4da0-9339-d5ff47ae902e)

![12](https://github.com/user-attachments/assets/eb211883-3751-4a89-a028-765f4326578f)

![13](https://github.com/user-attachments/assets/d09919ce-da29-428d-87d2-4fb0b5ad3063)

![14](https://github.com/user-attachments/assets/965c1076-7b72-4989-b721-6c435627fd21)

<h3>Configure Users (customers)</h3>
<p>Agent Panel -> Users -> Add New</p>

![15](https://github.com/user-attachments/assets/049b4cd3-f54c-42e2-a088-bb2154a288d3)

![16](https://github.com/user-attachments/assets/af06eb98-d496-4950-ab6f-550be7e5c8b0)

<h3>Configure SLA</h3>
<p>Admin Panel -> Manage -> SLA</p>
<p>Sev-A (Grace Period: 1 hour, Schedule: 24/7)</p>
<p>Sev-B (Grace Period: 4 hours, Schedule: 24/7)</p>
<p>Sev-C (Grace Period: 8 hours, Business Hours)</p>

![17](https://github.com/user-attachments/assets/89592448-1594-4fb8-ad6e-f2ff02332058)

![18](https://github.com/user-attachments/assets/383edc6c-0a37-4349-8122-fe4a697c9eb7)

![19](https://github.com/user-attachments/assets/569af357-9b21-4dab-83a6-0087d9cfb7b9)

<h3>Configure Help Topics (For when users create a ticket)</h3>
<p>Admin Panel -> Manage -> Help Topics</p>
<p>Business Critical Outage</p>
<p>Personal Computer Issues</p>
<p>Equipment Request</p>
<p>Password Reset</p>
<p>Other</p>

![20](https://github.com/user-attachments/assets/900b527d-7b5f-485b-a8c9-32186335e889)

![21](https://github.com/user-attachments/assets/9d8593e1-3c59-48f3-aeaa-7e5b8fcecac1)

![22](https://github.com/user-attachments/assets/bfade730-2388-4631-ab8f-7782a78cc0f7)

![23](https://github.com/user-attachments/assets/269ae5ec-9d03-4d0b-866e-4f60fb1ca785)

![24](https://github.com/user-attachments/assets/47c0c952-a778-4a50-ad66-9ea70ffb0536)
