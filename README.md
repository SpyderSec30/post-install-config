<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - post-install-config</h1>
Here we will configure Roles, Departments and Teams to demonstrate how tickets are handled in an IT environment<br />


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

<h2>Place Holder</h2>



</p>

