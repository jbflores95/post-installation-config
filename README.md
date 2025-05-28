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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>

![58](https://github.com/user-attachments/assets/5ef59f5b-c6d4-41d2-a361-e645ccf431f5)

</p>
<p>
- The Admin Panel is for system configuration and management (used by administrators)
</p>
- Agent Panel is for handling support tickets (used by help desk staff).
</p>
- To confirm you are in the Admin Panel, verify that the "Agent Panel" option is displayed in the top-right corner—this indicates you are currently in the administrative interface.
</p>
 - Next, we are going to configure a new role in the Admin Panel. Go to Agents > Roles > Add New Role
<br />

<p>

![59](https://github.com/user-attachments/assets/50898adb-da88-46de-9bdb-509ee895004e)
![60](https://github.com/user-attachments/assets/6ebfe27a-59b2-451b-aaed-188404148c7a)
![61](https://github.com/user-attachments/assets/2b56c6bf-3c2e-4bb6-b7a6-ff2384593098)

</p>
<p>
-  Name this role "Supreme Admin" and then click on the Permissions Tab.
</p>
- Since this is an Admin role, we want this to have all of the Permissions. Under Tickets, make sure you clicked on all 13 permissions. Go to the Tasks Tab and do the same.
</p>
- Then go to the Knowledge tab and check "Premade". You can now click Add Role.
</p>
<br />


<p>

![62](https://github.com/user-attachments/assets/43eb8f34-2297-47c9-b9d4-a6afc5c0e661)
![63](https://github.com/user-attachments/assets/47ec0a0a-cbf5-4980-804d-895cace2ed73)


</p>
<p>
- Next, we head off to make a new Department. In this Admin Panel, go to Agents > Departments and click on Add New Department.
</p>

</p>
<p>
- Now in the Settings Tab, Leave the Parent as "Top Level Department". Under that, you can name this "SysAdmins". We succesfully added SysADmin to the Departments.
</p>
<br />

<p>

![64](https://github.com/user-attachments/assets/ec99c20d-8765-47ac-af98-0b97aeaae91d)
![65](https://github.com/user-attachments/assets/6cdf5099-21cf-4160-97b4-05a0e9c02b06)

</p>
<p>
- Next, we will add a new Team. Stay in the ADmin Panel, click on Agents > Teams > Add New Team.
</p>
- In the Team tab, you can name this Team "Online Banking". Click Create Team.
<br />

</p>
<p>
oooooo
</p>
<br />

<p>

![66](https://github.com/user-attachments/assets/7927e7b5-747c-4363-b443-e12d76de79b4)

</p>
<p>
- Now, on the same screen, click on Settings > Users.
</p>
- Here we'll enable guest ticket submissions so users can submit tickets without needing an account. This allows end users to create tickets quickly without any registration steps. Make sure it's unchecked, then click Save Changes.
<br />

</p>
<p>
ppp
</p>
<br />

![67](https://github.com/user-attachments/assets/d2f277ce-d9e1-492d-8391-7c211f9263b0)
![68](https://github.com/user-attachments/assets/f88faf3c-87fd-48b4-b108-fedb2979a9d1)
![Screenshot 2025-05-27 182957](https://github.com/user-attachments/assets/8c87e948-3322-4b8a-abd1-3f148934bed0)

<p>

</p>
<p>
- We'll add Agents now. Go to Agents > Agents > Add New Agent.
</p> 
- In the Account tab, you can name this agent "Jane Doe". Enter whatever email you want.
</p>
- Username: jane
</p>
- Then click on Set Password, Uncheck "Send the agent a reset password", then enter "Password1" for the password. Uncheck Require password change at next login too, then click on Update.
<br />


</p>
<p>

</p>
<br />

<p>
<p>

![69](https://github.com/user-attachments/assets/60334b87-7cfd-4cc9-81b8-ce6c75e913f1)
![70](https://github.com/user-attachments/assets/2493afac-b6c1-4953-a1a5-82de5ac0e4af)

</p>
<p>
- Go to the Access tab and under Primary Department, select Sys Admins. To the right of it, Select Supreme Admin.
</p>
- Next, click on the Teams Tab and select Online Banking, and click Add! You can now click on Create.
<br />

<p>

![71](https://github.com/user-attachments/assets/18df32d2-677a-4b29-920b-c63c538af778)
![72](https://github.com/user-attachments/assets/dfb0aa2f-c200-4af6-b1bb-ec6640d70960)
</p>

<p>
-Let’s create another agent—click "Add New Agent" again. Name this agent John Doe, and for the email, you can use a placeholder since this is just for lab purposes. Set the password following the same method we used for Jane Doe earlier
</p>
- Next, navigate to the Access tab. Under Primary Department, select Support. Then, ensure you enable Expanded Access permissions (located to the right).
</p>
- Note: While "View Only" access may seem sufficient initially, selecting Expanded Access helps prevent workflow issues later in the lab environment.
</p>
<br />

<p>

![74](https://github.com/user-attachments/assets/417227ae-924f-4b90-b8a4-8a74816129ab)
![75](https://github.com/user-attachments/assets/9b1d2be2-2b0a-4f7a-808b-65b904bdb0b0)
![76](https://github.com/user-attachments/assets/22d0e206-c230-4202-98a4-a9b410408bce)

</p>
<p>
- Next we will add a User. Make sure you click on Agent Panel on the top right.
</p>
- Then go to Users > Add User.
</p>
- Next, create a placeholder email address for testing purposes—use karen@lognpacific.com and set the full name as "Karen."
<br />

<p>

![77](https://github.com/user-attachments/assets/42d94a60-656f-4fe8-a198-ce66ad9d9bc9)
</p>
<p>
- You can now see we have added Karen as a User. Good job if you made it this far with no problems. 😎 Next, we’ll configure SLAs (Service Level Agreements). To proceed, click Admin Panel in the top-right corner.
</p>
<br />

<p>

![78](https://github.com/user-attachments/assets/5876d744-ea35-48c1-82f5-92251c263cd0)

</p>
<p>
- In the Admin Panel, click on Manage > SLA > Add new SLA Plan.
</p>
<br />

<p>

![79](https://github.com/user-attachments/assets/33ecd261-4f72-4007-9e65-fdfaa9f44b16)
![80](https://github.com/user-attachments/assets/560e489f-e322-4caa-8e45-9973cecd71c0)
![81](https://github.com/user-attachments/assets/45bcdeb5-dbb0-4d34-837d-d60d6c24f3b7)

</p>
<p>
- Here we name this "Sev-A" > Grace Period: 1 Hour > Schedule: 24/7. Click on Add Plan.
</p>
- Next we name the second one "Sev-B" > Grace Period: 4 Hours > Schedue: 24/7. Click on Add Plan
</p>
- Lastly, name the last one "Sev-C" > Grace Period: 8 > Schedule: Monday-Friday 8 am- 5 pm with U.S Holidays. Click on Add Plan
</p>
- Congrats you have successfully added SLA plans. We will now move on to configure Help Topics.
</p>
<br />

</p>

![82](https://github.com/user-attachments/assets/f2a92151-206c-4b30-b998-11547bf57d3c)

</p>
<p>
- Now, in the Admin Panel, go to Manage > Help Topics > Add New Help Topics.
</p>
<br />

![83](https://github.com/user-attachments/assets/8fb45811-1682-4784-b628-57f28e174679)
![84](https://github.com/user-attachments/assets/fd5f5172-7759-4959-92a6-8fae49c007cb)

</p>
<p>
- For Topics we will choose Business Critical Outage > Parent Topic: Report a Problem. Click Add Topic.
</p>
- The next Topic will be for Personal Computer Issues. Parent Topic: Report a Problem. Click Add Topic
</p>
<br />

![Screenshot 2025-05-27 195952](https://github.com/user-attachments/assets/aac72f7e-e4a1-467a-a101-de3c4ef6843f)
![85](https://github.com/user-attachments/assets/52bc56ca-9357-42e6-af76-ebe444ac569f)
![86](https://github.com/user-attachments/assets/82b4082e-67c1-47e6-820c-e9bd55f268eb)

</p>
<p>
- Next Topic: Equipment Request, Parent Topic: General Inquiry. Click Add Topic
</p>
- Next Topic: Password Reset, Parent Topic: Report a Problem. Click Add Topic
</p>
- Last Topic: Other, Parent Topic: General Inquiry. Then, Click Add Topic.
</p>
<br />

![87](https://github.com/user-attachments/assets/052ffa97-cc8b-4e49-8d43-db67f5b91a3f)

</p>
<p>
- You can see all the Topics you just made here. Help Topics in osTicket serve a critical organizational purpose—they act as a categorization system for incoming tickets, ensuring requests are automatically routed to the correct department or team. 
</p>
- Congratulations! You’ve successfully completed the osTicket Post-Install Configuration lab. By setting up departments, agents, SLAs, and help topics, you’ve built the foundation for a streamlined ticketing system. Well done, now you’re ready to manage support requests like a pro! 💻 😎


<br />

<h2>Final Thoughts</h2>
<br />
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
