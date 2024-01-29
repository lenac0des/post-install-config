<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Configuration Setup</h1>
</p>
This tutorial demonstrates the post-configuration setup of the osTicket system.<br />

<p>

</p>
</p>
<p>
Now that we have successfully configured osTicket from scratch. It is time to do some system administration and work on some post-installation setup. First, we will configure new roles within the help desk. In order to do so, go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role," then enter the name of the new role. You can also modify any specific role permissions. In this case, since we are creating a Supreme Admin, they will be given all permissions. Remember that roles determine an agent's permissions, so not all agents will have unlimited access. If you followed the steps correctly, your screen should look like this. As you can see, we have successfully created the "Supreme Admin" role.
</p>
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/856482bf-6019-4f5b-85f7-a81f7d6d7c99" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<p>
</p>
<p>
Next, select the "Departments" button in the Agents tab. Here, we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case, we will make the "System Administrators" department. This is where the Supreme Admins will be designated. Other specific settings, such as SLAs, managers, and other e-mail settings, can be set up in the department's tab.
</p>
<br />
<p>
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/70c64162-e941-4d63-a431-adeb0f3cd10a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/6aa486e1-8351-4e40-ae4c-9a6e3ffb11b0" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
<p>
After configuring a new department, we will set up a new team. Teams allow you to pull agents from different departments, and you can have an A team with top technicians from specific departments. For example, you can create a help topic that correlates with a product you produce and assign it to a team of agents specializing in that particular product. To set up a team, go to Agents->Teams. A Level I support team has been created by default; we will make a Level II Support Team in this example.
</p>
<br />
<p>
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/88c2f5bb-b57f-4fe8-980e-07c4fc517219" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have set up a new team, we will create a new setting allowing anyone to create tickets. Admin Panel->Settings->User Settings.
</p>
<br />
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/a9295431-19d7-45e2-b4a8-5ab4d4665dd6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is now time to create Agents. Agents are the employees of the helpdesk who work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their departments. Agents can be provided access to departments other than their own and have different roles depending on their department. Permissions, Access, & Teams will be assigned in the Agents tab.
</p>
<br />
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/39485fb9-2f27-4a93-8625-0686f3e5caf6" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating some agents, we will create users. Users are customers who create tickets when they are having issues. A user is identified with their E-mail address. To create a user, follow this path: Agent Panel->Users->User Directory->Add new.
</p>
<br />
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/28180668-42e9-4171-a666-e7057316f01e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLAs Plans provide the time the help desk is expected to take to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule, and there is a grace period within that schedule. In this example, SEV-A has a 24/7 and a one-hour grace period.
<br />
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/340b0206-8a75-4b8d-9309-a9b2aeb8102b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help topics help users categorize their tickets. In the example below, we have made a helpful topic for "Business Critical Outage." This can be if customers cannot access mobile banking.
</p>
<br />
<img src="https://github.com/lenac0des/post-install-config/assets/71302899/532b4e2d-9491-42ac-bed8-039800c33c5d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
