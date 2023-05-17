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

- Configure Roles
- Configure Departments and Teams
- Configure Agents and Users
- Configure SLA's

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/vMAZLNh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After logging into osTicket as an admin via the virtual machine initally created, select agents then roles to select permissions and capabilities for each agent assigned with given role. By doing this it will determine the different "clearance levels" between all agents. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Zx0Dp3O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
By creating departments it allows for a more precise flow of ticket traffic and ensuring the correct agents with the needed knowledge base are working them. Along with creating teams of specific agents will ensure best execution on given ticket even if the ticket is out of the agents "department scope" access will still be availible being that said agent is a part of a specified team.
</p>
<br />

<p>
<img src="https://i.imgur.com/Xop7vnt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the admin portal we are able to create agent profiles consisting of their username, password, authentification preferences, along with assigning department and role to agent. The same can be done for a user by creating a user profile containing contact information. As a user you are given the abiblity to write "own" a ticket that is submitted.
</p>
<br />

<p>
<img src="https://i.imgur.com/quEGMag.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
setting SLA's determines the turnaround time period for a ticket to be resoved and the required maintenance of ticket while being worked. SLA's are also a fundemental part in ensuring tickets are handled in a logical manner, as well as in an appropriate time spand correlating directly with the "problem" itself.
</p>
<br />
