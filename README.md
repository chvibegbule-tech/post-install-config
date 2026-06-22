# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This project demonstrates the post-installation configuration of osTicket. The lab was performed in a Microsoft Azure virtual environment and focused on configuring roles, departments, teams, agents, users, SLAs, and help topics to simulate a real-world IT support environment.
The objective of this project was to gain hands-on experience with help desk administration, ticket management workflows, user administration, and service level management.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/19WpzGui8vw?si=mQsFPsRoOxi47OQu)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
- MySQL
- PHP Manager for IIS
- Windows Authentication
- Web Browser


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles

- Configure Departments

- Configure Teams

- Configure Agents (Help Desk Staff)

- Configure Users (Customers)

- Configure Service Level Agreements (SLAs)

- Configure Help Topics



<h2>Skills Demonstrated</h2>

- Ticket Management
- Customer Service
- Incident Response
- User Account Administration
- SLA Management
- Ticket Escalation
- Role-Based Access Control
- Department Administration
- Troubleshooting Workflows
- Documentation




<h2>Configuration Steps</h2>

<p>
Step 1: Configure Roles


Navigated to:

   - Admin Panel → Agents → Roles

Created a new role:
-
- Supreme Admin and assigned full permissions

Skills Demonstrated:
-
- Access Control
- Role-Based Access Control (RBAC)
- User Administration
</p>
<p>
<img width="3360" height="2100" alt="Screenshot 2026-06-21 at 6 08 51 PM" src="https://github.com/user-attachments/assets/bed436f4-f6a3-4678-bdc7-f6a88f06f5c5" />

</p>
<p>
Roles determine the permissions assigned to agents.
</p>
<br />

---

Step 2: Configure Departments
-
<p>

Actions Performed:
-
Created departments such as:

- Help Desk
- SysAdmins
- Networking
- Security

Navigation:

Admin Panel → Agents → Departments

Skills Demonstrated:
-
- Organizational Structure Design
- Ticket Routing
- Department Management

<img width="3360" height="1961" alt="Screenshot 2026-06-21 at 6 34 50 PM" src="https://github.com/user-attachments/assets/88ac3f7d-df90-43fd-8a30-75365eee3a28" />


<p>



</p>
<p>
Departments organize support functions within the organization.
</p>
<br />

---

Step 3: Configure Teams
-
Actions Performed:
-
- Created: Online Banking Team
- Created: Infrastructure Team
- Created: Security Team

Navigation:
-
Admin Panel → Agents → Teams

Skills Demonstrated:
-
- Cross-functional Collaboration
- Ticket Escalation Management


<p>
<img width="3328" height="2004" alt="Screenshot 2026-06-21 at 7 25 15 PM" src="https://github.com/user-attachments/assets/98a60c7d-dc00-44cb-9ac7-0525e69c7d6d" />

</p>
<p>
Teams allow agents from different departments to collaborate.
</p>
<br />

---

Step 4: Configure Agents
-

Actions Performed:

Created agents:
-
- Jane Doe
- John Doe

Assigned:

- Roles
- Departments
- Teams

Navigation:

Admin Panel → Agents → Add New

Skills Demonstrated:
- User Administration
- Permission Management
- Help Desk Operations

<img width="3306" height="1930" alt="Screenshot 2026-06-21 at 7 44 27 PM" src="https://github.com/user-attachments/assets/e2c8cc53-83f1-4d60-9619-b76f3225bb64" />
</p>
<p>
Agents are support personnel who work on tickets.

---

Step 5: Configure Users
-

Actions Performed

Created users such as:

- Karen
- Ken

Navigation:

Agent Panel → Users → Add User

Skills Demonstrated:
- Customer Management
- End User Administration

<img width="3306" height="1930" alt="Screenshot 2026-06-21 at 8 00 30 PM" src="https://github.com/user-attachments/assets/76d4fe6c-387c-4334-a40f-e98d7ede77db" />
</p>
<p>
Users represent customers who submit tickets.

---

Step 6: Configure SLA Plans
-

Actions Performed:

Created:
-
- Sev-A (Grace Period: 1 hour, Schedule: 24/7)
- Sev-B (Grace Period: 4 hours, Schedule: 24/7)
- Sev-C (Grace Period: 8 hours, Business Hours)

Navigation:

Admin Panel → Manage → SLA

Skills Demonstrated:

- Service Management
- Incident Response
- Priority Management

<img width="3306" height="1930" alt="Screenshot 2026-06-21 at 8 10 09 PM" src="https://github.com/user-attachments/assets/39746678-a007-4615-af06-a5aed3cde845" />
</p>
<p>
SLAs determine ticket response and resolution expectations.

---

Step 7: Configure Help Topics
-

Actions Performed

Created:

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset


Navigation:

Admin Panel → Manage → Help Topics

Skills Demonstrated:

- Ticket Categorization
- ITSM Concepts
- Workflow Design
<img width="3306" height="1930" alt="Screenshot 2026-06-21 at 8 33 16 PM" src="https://github.com/user-attachments/assets/094baf0b-42fb-4829-b665-cf8a6d20a883" />
</p>
<p>
Help Topics categorize tickets.

