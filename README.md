<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial will be the post-install configuration of the help desk ticketing system, osTicket. We will configure roles, departments, teams, agents, users, SLA's, and help topics.<br />
<h2>Prerequisites</h2>
<p>Install osTicket www.github.com/kmccalltech/osticket-prereqs</p>
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>

<table>
  <tr>
    <td>
      <img height="170%" width="170%" alt="Screenshot" src="https://i.imgur.com/ldP7Tsg.png" />
    </td>
    <td>
      <img height="80%" width="80%" alt="Screenshot" src="https://i.imgur.com/y7RGugh.png" />
    </td>
    </tr>
    </table>

</p>
<p>
  The first thing we want to do is make sure you are on the Admin panel. If the top right status says "Agent Panel" then we know we are in the Admin panel. 
</p>
<p>Create a role by navigating to Agents -> Roles. We can name this role "Senior Admin". In the permissions tab, select every permission for this role. Be sure to go through every permission tab for this role. Finish by "Add Role"
</p>
<br />

<P><img height="80%" width="80%" alt="Screenshot" src="https://i.imgur.com/dgmK1jS.png" />
</P>
<p>
  Configure departments by navigating to Agents -> Departments. Select Top Level Department and name the department System Administrators.
</p>
<br />

<p>
<img height="80%" width="80%" alt="Screenshot" src="https://i.imgur.com/Ybv7ZBL.png" />
</p>
<p>
Configure teams by navigating to Agents -> Teams. We can name this team "Accounting". Next, we can  create some agents, they can be added to this team.
</p>
<br />

<p>
  <table>
    <tr>
      <td>
          <img width="962" alt="Screenshot" src="https://i.imgur.com/NzcCXLm.png" />
      </td>
      <td>
      <img width="957" alt="Screenshot" src="https://i.imgur.com/TIJcmvI.png" />
      </td>
    </tr>
  </table>
</p>
<p>
  Configure a few agents by navigating to Agents -> Add New. We can create a new agent named "Peter Parker" and set his login credentials by clicking "set password".
</p>
<p>We can give this agent a department and assign this agent the Senior Admin role we created earlier. In the Permissions and Teams tab, we can give the agent all permissions and assign his to the "Accounting" team.</p>
<br />

<table><tr>
  <td><img height="140%" width="140%" alt="Screenshot" src="https://i.imgur.com/iK3ed78.png" />
</td>
  <td><img height="160%" width="160%" alt="Screenshot" src="https://i.imgur.com/FEnk2e3.png" />
</td>
</tr></table>
<p>
Configure another agent and assign this agent the Support role in the Access tab with All Access. Choose what permissions he can have in the Permissions tab. I will be using him in our ticket response lab, so I'm going to give him just enough access to handle those tickets.</p>
<br />

<table>
  <tr>
    <td>
<img width="958" alt="Screenshot" src="https://i.imgur.com/xX99wPy.png" />
    </td>
    <td>
<img width="961" alt="Screenshot" src="https://i.imgur.com/kvWoDqJ.png" />
    </td>
  </tr>
</table>
<p>
  Create a few users by navigating to Agent Panel (on the top right it should say "Admin Panel") -> Users -> Add New. We will use them in the next lab as well, They will be the ones submitting the tickets to our agents.
</p>
<br />

<table>
  <tr>
    <td><img width="959" alt="Screenshot" src="https://i.imgur.com/5vociOg.png" />
</td>
    <td>
      <img width="958" alt="Screenshot" src="https://i.imgur.com/j0KY1sy.png" />
    </td>
  </tr>
</table>
<p>
Navigate back to the Admin Panel so we can create SLA's by navigating to Manage -> SLA
</p>
  <p>
    Configure a few different SLAs with various schedules and grace periods. These will be used in our ticket response lab to determine the urgency of various tickets. 
  </p>
  <br>
  
<img height="80%" width="80%" alt="Screenshot" src="https://i.imgur.com/BQBigcp.png" />
<p> Configure Help Topics by navigating to Manage -> Help Topics. Their priorities and various other items can be configured in the New ticket options tab.
</p>

<p>Several help topics can be created.</p>
  <p>
    <img height="80%" width="80%" alt="Screenshot" src="https://i.imgur.com/q28iSCy.png" />

  </p>
  <P> Here are a few help topics that I created.</P>

**This completes our configuration lab. Next will be the Ticket Response Lab, see you there!**
