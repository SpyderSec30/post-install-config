<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - post-install-config</h1>

- Roles
- Departments
- Teams

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>
 
- Windows 10</b> (21H2)

<h2>Getting Started</h2>
<p>Sign back into Microsoft Azure and get the IP address of your Windows virtual machine. Then with the right credentials use RDP to connect back to it. Open a web browser (edge) and navigate to localhost/osTicket/scp/login.php, if you did everything in the <a href="https://github.com/SpyderSec30/osticket-prereqs">osTicket-Prereqs</a> lab your instance of osTicket should still be up and running.</p>

<h2>Admin Panel vs Agent Panel</h2>
<p>The Admin panel is designed for system administrators and provides comprehensive control over the osTicket system. Key features include:

- System Settings
- User Management
- Departments
- SLA plans

The Agent panel is intended for agents who handle and resolve tickets. Key features include:

- Ticket Mangement
- Ticket Filters
- Task Management
- Collaborations

The panel your currently in is determined in the top-right corner next to your name. If it says Admin panel then your in the agent panel, to get to the Admin panel you'll need to click the button and you will be taken to the Admin panel. (Note that that the button now says Agent Panel)

<h2>Agent Panel</h2>
<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/93c2c827-7fd6-41c5-868d-a915e32321a9"/>

<h2>Admin Panel</h2>
<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/87aa5f51-8997-405e-8b33-95a0a82c9118"/>


<h2>Roles</h2>
Roles are the permissions granted to Agents per Department that they have access to. To configure rolls make sure your in the Admins panel, then select the Agents tab and inside you'll see Roles.<br></br>

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/e118ef7a-bfc3-4c4b-816f-9920e865b500"/></br>

As you can see, you can see all roles that are active. You can also create a new role from this screen by selecting "Add New Role" located on the same line as Roles

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/6bec8ae0-24d4-4a27-8340-acc157dd996a"/>

<h2>Departments</h2>
Inside the Admin panel, you'll select the Agents tab and right next to Roles you'll find Departments. Since tickets are routed through Departments in the help desk, there are many settings that can be set for each Department. For this Lab I just Created a basic System Admins department.<br></br>

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/be19354a-7964-4f8b-a888-ba3c8f48ff1d"/><br></br>

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/cdad4fc5-ed0d-4a50-b603-28f6d4b25c21"/><br></br>

<h2>Teams</h2>
Inside the Admin panel, you'll see Teams to the left of Roles. Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via Help Topic of Ticket Filter. We will make a simple Level II support team. In the members tab you can add your admin account to this team.<br></br>

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/f2fff7bf-678f-44f3-aa63-a9af2ff1422d"/><br></br>

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/e956c717-67b2-4f7e-b364-ab30037c222d"/><br></br>

<h2>Settings</h2>
We need to configure the settings to allow anyone to be able to create a ticket. Inside the Admin panel select the settings tab located on the same line as the Agents tab we used to configure Roles, Departments and Teams. Next click the sub-tab Users. Make sure Require registration and login to create tickets is unchecked.<br></br>

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/f7a97b59-fb85-4143-9e23-48238d9bcf5e"/><br></br>

<h2>Agents</h2>
Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a primary Department and given a primary Role for Tickets/Tasks routed to that department.<br></br>

<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/e6975e91-71d8-444a-9627-b1f180308fb5"/><br></br>

Make two users, set your own username and password for these users. Be sure to explore the Access, Permissions, and Teams tab to configure there role in the company. For this lab, when you create John Doe. Under the Access Tab, make him part of the support team and make his role view only.

- Jane Doe
- John Doe
  
<img src="https://github.com/SpyderSec30/osticket-prereqs/assets/174487140/df05a05a-e3e9-43f2-9995-a97b13b0c180"/><br></br>

<h2>Users</h2>
For the purpose of this lab we will create users who can create tickets so that we can view the process and the life of a ticket in an IT environment.
</p>

