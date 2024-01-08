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
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 


<h2>Configuration Steps</h2>

<p>
  
![Screenshot (140)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/ec742316-543f-4082-a390-83c97017e76d)


![Screenshot (142)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/7610697f-27c8-4215-81dc-84809261275b)




</p>
<p>
After installing osTicket, it is now time to make configurations to use it as a ticketing system. One thing to note is that I switch between Admin and Agent panels as each panel has different configurations. To tell which panel is used, look at the top right of the osTicket screen. If it reads Agent Panel, the Admin panel is the one being used and vice versa.

The first step to take is to make a new role called Supreme Admin. For the purposes of this lab, I am intentionally creating a role that has every permission that can be granted. To create a new role, open the Admin panel enter the Agents Menu. Click on Roles and create the new role from there.


</p>
<br />

<p>
  
![Screenshot (143)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/4dd99748-9bce-43af-aa5d-8c22c6c1b001)


</p>
<p>
Next, a new Department will be created for System Administrators. In the Admin panel, open the Agents menu and click on Departments to create a new Department within osTicket.
</p>
<br />

<p>

![Screenshot (144)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/e72240e1-4ee3-40d8-96ea-2af99af0be7f)



</p>
<p>
A new Level II Support Team will have to be created to supplement the Level I Support Team already made within osTicket. To create a new Team, enter the Admin panel and open the Agents menu. Click on Teams and add any new teams that need to be created.
</p>
<br />

![Screenshot (147)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/035660de-4414-4911-ba84-59b2b83dfbcf)



 Now its time to add a new agent 
 

![Screenshot (148)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/09c149dc-9e73-4367-a6be-1958696acd61)

![Screenshot (149)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/6d2f3925-29ba-47b3-af3c-d298ae82044d)


New agents will have to be created so they can take tickets that come to the queue. To create new agents, enter the Admin panel and open the Agents menu. Click on Add New Agent and create the account credentials for each new agent. In this case, Jane and John Doe are created.


Next Service Level Agreements (SLAs) will have to be made in order to categorize tickets according to their level of impact. To make new SLAs, enter the Admin panel and open the Manage menu. Click on SLA and create any needed SLAs. In this case, SEV-A, B, and C have been created to categorize tickets that need to be resolved within 1 hour, 4 hours, and 8 hours respectively.


![Screenshot (153)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/4c2adf93-3fd1-4e18-bc68-9904eba9dc1c)


Finally, Help Topics need to be created to help users select an appropriate category that describes their problem so that Agents get an idea of what problem is described in the ticket. To make a new Help Topic, enter the Admin panel and open the Manage menu. Click on Help Topics and click on Add New Help Topic. In this case, I have added the following in order to use later for when I create new tickets to resolve: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Request.


![Screenshot (154)](https://github.com/JoshuaMoorecc/post-install-config/assets/154629831/91832380-b945-464d-93eb-3bc5c2e0617a)



<h1>osTicket Configurations are Complete</h1>


Now that the configurations have been set in place, We can now utilize osTicket as a proper ticketing system. We can create tickets and be able to traige them as if we were in a real environment.









