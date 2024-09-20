<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Post-Install Configuration</h1>
This tutorial goes through the basic post-install configuration of the osTicket.<br /><br><br><br><br>


This is not going to be a complete comprehensive guide. We’re going to get a sense of how to navigate through osTicekt and see an asortment of tabs as we set up osTickets with very basic configurations.

Okay, let's get started.

Well actually, before that let's briefly mention the two panels we'll be switching between: the Admin Panel and Agent Panel. 
The Admin Panel is backend configuration and the Agent Panel is for users that are handling tickets.

Okay, now what we’ll do first is add a new Role. Roles tell each user what their allowed to do within osTicket.
So, lets click Admin Panel in the upper right.

![1](https://github.com/user-attachments/assets/270800f8-c87b-4f54-8928-6f51d60e9988)<br><br><br><br>



Click on the Agents tab, then click on Roles and then add new role.

![2](https://github.com/user-attachments/assets/bcde9fe0-14c3-407a-9515-f3940636fffd)<br><br><br><br>


Type in the name of the new role you want, in this case I’ll use Supreme Admin. 

![3](https://github.com/user-attachments/assets/99dfdfef-ca6a-4dc0-ae88-af1fc50a957b)<br><br><br><br>



Select the Permissions tab and select the permissions you want for the role. 
We’ll check all boxes from all three tabs for the Supreme Admin role.
And then click Add Role.

![4](https://github.com/user-attachments/assets/776eddcb-1000-4414-babc-c957d6fe3c06)<br><br><br><br>


We could create a wide range of roles with various combinations of permissions but for now, lets head over to the department section.

Click on the departments tab and click Add new department.

![5](https://github.com/user-attachments/assets/6fea3b06-03c1-43a2-b733-970f81bb2683)<br><br><br><br>


The department sections can be used for ticket visibility, say if you have a networking department, you can set up their department so they can only see tickets for their department where a sysadmin department will be able to see all tickets.
Here, we simply need to fill out the name field for the department and click Create Dept.

![6](https://github.com/user-attachments/assets/175c76c0-ad2b-4b93-a644-784e8df57280)

The rest of the fields in this tab are optional. We’ve filled out all that’s required to create a new department. And you can assign agents in the Access tab next to the Settings tab.
For now, let’s head over to the Teams section.<br><br><br><br>

Teams are for creating a group of people who are from different departments. For instance, you’d have a Sys Admin and helpdesk agents pulled together from different departments to form the Online Distribution team.
![7](https://github.com/user-attachments/assets/3360eb54-7d5a-4d9a-9d22-0ddd1797e21f)<br>
Adding a new team is simple too. Click on teams, then add new team, now you simply assign a name and fill out any other information that you require, such as the team lead and other members of the team.<br><br><br><br>


To enable required registration to create a ticket, go to the settings tab and click users.
On this tab you'll need to click Require registration and login to create tickets. Then click Save Changes.

![8](https://github.com/user-attachments/assets/3c8bceba-1eed-4811-9bf7-7913b3623b9d)<br><br><br><br>



Up next, We're going to create an Agent to handle Tickets. Click the Agents tab, then the other agents tab, and then add new agent.
Fill out the necessary fields and click set password.

![9](https://github.com/user-attachments/assets/f4b96b06-8497-4b23-8ff8-79d01ba40e9b)<br><br><br><br>


Uncheck Send the agent a password reset email. Or keep it checked if that’s what you prefer in your environment.

![10](https://github.com/user-attachments/assets/31638473-3531-472a-b626-9829d3c4faed)<br><br><br><br>


Create the password and decide if you need to keep the box checked that says Require password change at next login.
Then click set.

![11](https://github.com/user-attachments/assets/8330bdb7-a463-44c6-9f65-d3bfd825704f)<br><br><br><br>



Now, we’ll assign the agent's department and their role. The role determines what the agent is able to do, from just viewing tickets to being able to fully edit, reply, and resolve a ticket.

![14](https://github.com/user-attachments/assets/28ef8ac9-3097-4ae1-b9e7-93a12dfa78ba)
After we've done that, we'll click create.<br><br><br><br>



Now, we’re going to create a User.<br>
To do this we’ll need to go to the agents panel, which is in the upper right corner.

![15](https://github.com/user-attachments/assets/9fb1818a-1238-49b6-8821-6914fbeb4769)<br><br><br><br>


Click Users -> User Directory -> Add User.


![16](https://github.com/user-attachments/assets/4298d1e6-e7f6-4670-a175-61954196edef)<br><br><br><br>


We’ll fill out the necessary fields and then click Add User.


![17](https://github.com/user-attachments/assets/e3da1925-1feb-4695-9777-2c4d24f41bfe)<br><br><br><br>


After you create a user click on Register.

![18](https://github.com/user-attachments/assets/1b379302-307a-451c-af64-154648e9f980)<br><br><br><br>


We can just click Create Account

![19](https://github.com/user-attachments/assets/d7cc860a-31fe-4a56-8d72-6265c0563fe6)<br><br><br><br>


Or we can uncheck Send Account activation email to User and then fill out a password for them along with selecting a few other settings.

![20](https://github.com/user-attachments/assets/80d62380-861d-44b8-a9e6-44162b904283)<br><br><br>



When we're done, click Create Account.
This will enable the user to register on the user support ticket portal so they can create tickets.

![12](https://github.com/user-attachments/assets/0af0541b-de0d-46b5-9ca8-10e36ee3d089)


![13](https://github.com/user-attachments/assets/0e41c171-e542-453f-b074-431b6dfcec2f)<br><br><br><br>



And finally, SLAs. An SLA (Service Level Agreement) is basically how much time you have to do a specific task such as responding to a ticket or resolving a ticket.
To configure SLAs, we’ll click on the admin panel in the upper right

 


Then the Manage tab -> SLA tab -> Add New SLA Plan.

![22](https://github.com/user-attachments/assets/143c792f-fa2d-43fc-91dc-61320100d95a)<br><br><br><br><br><br>



In this panel, we’ll fill out the necessary fields to create an SLA Plan for Sev-A. When we’re done, we’ll click Add Plan and repeat the process for subsequent SLA Plans, Sev-B, and Sev-C.

The names are usually associated with Sevs and denote the severity of the ticket.
Sev-A, Sev-B, Sev-C. 

Grace Period is how much time we have to respond to a ticket.

Schedule determines when grace periods are in affect.

- 24/5 = 24 hours a day 5 days a week, Monday – Friday.
- 24/7 = 24 hours a day 7 days a week, Monday – Sunday.
- Monday – Friday = 8a.m. to 5p.m. with U.S. Holidays. – business hours.

![23](https://github.com/user-attachments/assets/bcc8c32d-047d-4ac9-b1f4-03c4a530b549)<br><br><br><br>


And finally, if we want to create Help Topics for users to apply to their tickets, (A Help Topic is basically a category that can be assigned to a ticket.) we’ll click the Help Topics tab and then click
Add New Help Topic.

![24](https://github.com/user-attachments/assets/1f578c2e-6885-4b1d-842c-c88a831244c8)<br><br><br><br>



Now we’ll just need to fill out the required fields and click Add Topic.

![25](https://github.com/user-attachments/assets/ab44e2c5-7816-4956-bd56-aa28a069e5d2)<br><br><br><br>



If you require any additional help with any of the fields in any of the tabs the ? next to each field reveals more information about it.

![26](https://github.com/user-attachments/assets/5edc3c8a-d359-43cd-8aed-c3127c228b53)<br><br><br><br>


And that's it. We’re all done.
