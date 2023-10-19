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
- Configure Departments
- Configure Teams
- Ticket Creation
- Configure Agents (Help Desk Workers)
- Configure Users (Customers)
- Configure SLA (Service Level Agreement)
- Configure Help Topics


## Configure Roles

In order to configure roles within osTicket:
  - Login to osTicket with the previously created credentials
  - Navigate to the Admin Panel
    
   <img width="778" alt="adminpanel" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/a36208ed-bafb-456e-8acf-5a83d96b97f8">
   
  - Click on "Agents"
    
   <img width="777" alt="agents" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/d080ff15-3896-4c55-8fd2-3cd8f87f4b7b">

  - Click on "Roles"

   <img width="777" alt="roles" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/7dff27a1-dbdd-49a6-9b28-293bc1384fa4">

  - Click on "Add new role"

   <img width="777" alt="addnewrole" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/b541a374-1a2e-412c-8ee1-5886bfdeeefd">

   - Create a "Super Admin" role
     
  <img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/64901a2e-ed5c-4ab4-8ae9-5675eae09bd5">

  - Click on "Permissions" and check all the boxes under the "Tickets", "Tasks", and "Knowledgebase" tabs to enable full access for the "Super Admin" user.
  - Click "Add role" to put changes into effect

  <img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/5d556b63-ceeb-4e9b-a9fe-f75b5867a06c">

  - The new user is  now visible

  <img width="778" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/58ae0bf8-38c2-4ab6-99c8-07ad7edf1201">


## Configure Departments

  - Within the admin panel, click on "Agents"

  <img width="777" alt="agents2" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/57e41f3e-3b8a-4c94-bf9e-6764ed66e2d7">

  - Click on "Departments"
  - By default, the departments "Maintenance" and "Support" are available

 <img width="776" alt="departments" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/0be1150c-af3f-43b6-ad78-d8d4a26de776">

  - Click on "Add New Department"

 <img width="778" alt="addnewdept" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/c0721035-3936-4eed-8749-8ba8b6cd1a45">

  - Type in the name for the new department (The name for the new department in "System Administrators"
  - Click on "Create Dept" below to create the new department

 <img width="637" alt="createsysadindept" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/c97447ba-2408-45c0-9d81-53910145ad98">

  - The newly created department is now visible

 <img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/98b6d074-aa20-40b0-9432-8dc50a2c02e7">

    
## Configure Teams
     

  - Within the Admin panel, click on "Teams"
  - Click on "Add New Team"

<img width="775" alt="teams2" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/77895633-36ef-436e-867f-77572b51c044">

  - Type in a name for the team (The name of the team here is "Level II Support")

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/edc0d25c-9da5-490d-94dd-25d7ffad93ca">

  - Click on the "Members" tab to add a member to the team (Since there are no other members available yet, I will add myself to the team)

<img width="775" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/d6d8658a-27aa-4f09-abaa-9a660b04f0d7">

  - Click on "Create Team" to add the new team
  - The new team is visible on the dashboard now

<img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/4b94ede1-49e1-41fb-a15b-ed86b3072d82">

### Configuring Ticket Creation for all users

  - Navigate to the Admin Panel > Settings > Users Settings
  - Make sure the setting "Require registration and login to create tickets" remains unchecked so that all users have     the ability to create tickets

<img width="779" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/9a6e9fcf-a507-4fbe-b694-ba431442ec76">


## Configure Agents (Help Desk Workers)

  - Agents are the actual Help Desk employees that will be using the osTicket system to work on tickets
  - In order to create an angents, navigate to Admin Panel > Agents > Add New Agent

<img width="775" alt="addnewagent" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/e3301ab2-0274-4131-a17c-a9b04187fe7e">

  - Create a new user with the following information:
      - First Name
      - Last Name
      - Email
      - Username
      - Password


<img width="777" alt="janedoeuser" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/f28070b6-ae06-4ebb-b4ae-840636ecf2b7">

  - When setting the agent password, uncheck the the "Send the agent a password reset email" and "Require password change at next login" (This is done just for ease of use during testing and can be changed back later)
  - Press "Set" to set the password

<img width="487" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/b22f0633-2373-4ee8-8e52-0dd33546542b">


 - Assign access to the newly created agent
 - In this case, we will assign Jane Doe to the "System Administrators Department" as a "Super Admin"

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/333378e4-9175-4084-9deb-e4b9f3ff4548">

- Assign Jane Doe to the team "Level II Support" by clicking on the "Teams" tab and choosing "Level II Support" from the drop down menu

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/df512b20-6d2b-4788-aa26-4b3aafa05641">

- The newly created user is now visile on the "Agents" dashboard

<img width="778" alt="janedoenew" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/6094080c-59ec-4ffb-a70c-98601bb73539">

- Following the same procedure as above, create another Agents (This agent will be named John Doe, and will be assigned to the support department)

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/4b70adc2-fcad-46e0-b654-62eacdfcd197">


## Configure Users (Customers)

 - The users are the customers that will be using the osTicket platform to create tickets which will be worked on by agents
 - In order to create users:
 
 -  Switch to the "Agent" panel

<img width="778" alt="agentpanel" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/2f6c626f-ce9e-49d1-910e-a9aa15159dbd">


 -  Navigate to the "Users" tab
 
<img width="778" alt="agentpanelusers" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/3a2d49dc-21d2-4237-99b3-a6fa2e80e230">


 -  Click on "Add User"

<img width="776" alt="agentpaneladduser" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/0c827b33-0829-4da3-8e82-b9a7ecfb08dd">


- Enter in the information for the new user such as their email address and full name
- Click "Add User" to create the new user

<img width="777" alt="adduser" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/bc01eb02-658b-4361-b6db-7ac22739bdd2">


- The new user should now be visible in the "Users" dashboard

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/47251121-db4d-49d8-b1bf-011de1b6207e">

- Add another user by following the same procedure as above

- The new users are now visible on the "Users" dashboard

<img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/1c78fe40-e3af-439f-ae0a-0cabd9d8f9d5">


## Configure SLA (Service Level Agreement)

- The SLAs within osTicket have many custom options, for this instance, I will configure the SLA as the length of time in which the help desk Administrator expects tickets to be closed
- In order to configure the SLA

- Navigate to the "Admin" panel > Click on the "Manage" tab > Click on "SLA"

<img width="777" alt="adminpanelsla" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/b9500165-c025-4ecb-9ff1-6957f1b85d9d">


- Click on "Add New SLA Plan"

<img width="778" alt="addnewsla" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/2b153c26-2a0e-49be-b470-63edb5f1b7bc">

  
- The first SLA is named "SEV-A" and it will be given a 24/7 Schedule, meaning that if somwthing happens even on the weekend, the ticket must be solved.
  
- The Grace Period indicates the time in which the ticket must be resolved. I will enter in "1" for the Grace Period to indicate that the ticket must be resolved within one hour on a 24/7 Schedule.

- Click on "Add Plan" to create the new SLA

<img width="776" alt="sevA" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/ad894c90-3814-4e24-9971-f0677cbfb098">


- The newly created SLA plan is visible on the "SLA" dashboard now

<img width="778" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/83cd47cf-4894-4108-901b-91a57ae2066d">


- Following the same procedure, create another SLA titled "SEV-B" with a grace period of 4 hours on a 24/7 time schedule

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/02999fa7-08e6-425f-9945-c976cd7a8791">

- Create another SLA titled "SEV-C" with a grace period of 8 hours on a normal business hours schedule

<img width="778" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/0ae00d06-120e-4ff2-9754-ee4e899de3ab">


- All the newly created SLAs are now visible on the SLA dashboard

<img width="776" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/0132830c-f67a-4662-b53d-ee3d1063b195">


## Configure Help Topics

Help Topics in osTicket helps in streamlining the end-user's help desk experience to ensure proper assignment and prompt response to tickets. 

- In order to configure Help Topics, navigate to the Admin Panel > Click on the "Manage" tab > Click on the "Help Topics" tab > Click on "Add New Help Topic"

<img width="776" alt="helptopics2" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/eeb364ef-7c87-4cfe-ad17-434250851d78">

- Create a new Help Topic titled "Business Critical Outage"

<img width="776" alt="businesscrtout2" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/1e010b2d-1a31-4fb4-8f85-b3f91bc41107">

- The new Help Topic will be created

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/f955d7ee-849e-4285-bc15-dc7c30c8c058">

- Using the same procedure create three more help topics under the titles
  - "Personal Computer Issues"
  - "Equipment Request"
  - "Password Reset"

- All the newly created Help Topics are now visible on the "Help Topics" dashboard

<img width="777" alt="image" src="https://github.com/DamianPreslyPerera/osTicket-post-install/assets/89204562/b3242a63-f9b7-4aba-95bb-7efb3d0c5d8a">
















  
