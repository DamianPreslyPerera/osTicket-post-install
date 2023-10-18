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
- Configure Agents (Workers)
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








 













  
