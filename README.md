<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>
-PHP Manager for IIS 
-Rewrite Module
- PHP 7.3.8
-VC_redist.x86.exe
-MySQL 5.5.62
-osTicket
-HeidiSQL.
-Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2> 
Please follow these instructions the examples given are optional

**Configuring Roles:**

1. Log in to your osTicket admin panel.

2. In the admin panel, navigate to "Agents" and select "Roles."

3. To create a role called "Supreme Admin," click on the "Add New Role" button.

4. Set the permissions for this role to have access to all features and settings, essentially making it the highest-level admin role.

**Configuring Departments:**

1. In the admin panel, go to "Agents" and select "Departments."

2. Create a department called "System Administrators" if it doesn't already exist. Assign this department relevant agents or teams.

**Configuring Teams:**

1. In the admin panel, navigate to "Agents" and select "Teams."

2. Create two teams: "Level I Support" and "Level II Support" if they don't already exist.

3. Assign agents to their respective teams based on their responsibilities within your support system.

**Allow Anyone to Create Tickets:**

1. In the admin panel, go to "Settings" and select "User Settings."

2. Set the option "Allow anyone to create tickets" to enable. This allows both registered and unregistered users to create tickets.

**Registration Required:**

1. In the admin panel, under "Settings" and "User Settings," set "Registration Required" to require registration and login to create tickets. This ensures user authentication before ticket submission.

**Configuring Agents (Workers):**

1. In the admin panel, go to "Agents" and select "Add New."

2. Add agents like "Jane" and "John" by providing their details. Assign them roles based on their responsibilities.

**Configuring Users (Customers):**

1. Access the Agent Panel, which is a separate interface for agents.

2. Go to "Users" and select "Add New."

3. Add customers such as "Karen" and "Ken" by providing their information.

**Configuring SLA (Service Level Agreements):**

1. In the admin panel, navigate to "Manage" and select "SLA."

2. Create SLA policies for different service levels like Sev-A, Sev-B, and Sev-C. Set the response and resolution times according to your organization's requirements (e.g., 1 hour for Sev-A, 4 hours for Sev-B, and 8 hours for Sev-C).

**Configuring Help Topics:**

1. In the admin panel, go to "Manage" and select "Help Topics."

2. Create help topics for various types of requests, such as "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."

3. Assign these help topics to relevant departments or teams to categorize and streamline ticket submissions.

By following these steps, you'll have successfully configured roles, teams, permissions, and other settings in osTicket post-installation, allowing you to effectively manage your support system with different user roles and access levels. The osTicket will stop you and highlight any needed information for creation.

