# post-install-config-1
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- OSTicket System

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Admin Panel Settings 
- Configure Department
- Configure Teams (Level I or Level II)
- Configure Agents and Permissions
- Configure Users 
- Configure SLA Level
- Configure Help Topics



<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/ChH6BrA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the OSTicketing system is installed. I first configure the "Admin Panel". Next, is to configure the system and the roles in order to start submitting and resolving mock tickets. 

</p>
<br />

<p>
<img src="https://i.imgur.com/kFX7Tdn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/EsyYSAD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Once the OSticket install is complete, I started configuring the admin profile. After, I logged into OSticket as the admin and it will open up to the homepage. I set up the departments staying in the "Admin Panel" and under the "Agents tab" I will click on "Departments" and then click on "Add New Department". Then I named the department to eventually add agents who can submit and work on tickets. After I configured the teams to designate the agents on certain teams/levels. to create the teams I stayed in the admin panel and selected the "teams tab" and created two teams named Level I and Level II support. The configured it so that anyone can create tickets by staying in the admin panel and I clicked on the settings tab. Then under the user's section making sure the making the "Require registration and login to create tickets" box is unchecked. 

<br />

<p>
<img src="https://imgur.com/Whm00np.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/issTz0u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, I began configuring the agents in the admin panel. To do this, I clicked on the "Agents" tab and selected "Add New Agent." I then filled out their name and assigned a password. Next, I assigned them to their respective departments and roles. After completing this, I proceeded to configure the users by navigating to the "Agent Panel" and selecting the "User" tab. From there, I clicked on "Add New User" and submitted their name and email information. Once this was done, I returned to the "Admin Panel" and clicked on the "Manage" tab. Under this tab, I selected "SLA" and clicked on "Add New SLA Plan." I set up three different levels, Sev A, B, and C, along with their respective resolution grace periods. Once the SLAs were established, I proceeded to configure the help topics under the admin panel. Under the "Manage" tab, I clicked on "Help Topics" and selected "Add New Topic." I created a title for the topic and saved my changes.
</p>
<br />
