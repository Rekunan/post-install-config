# osTicket - Post-Install Configuration

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 (21H2)

## Configuration Steps
- Go to `localhost/osTicket/scp/settings.php`
- Click `Admin Panel` at the top right

![](https://safe.reku.me/C6VkC1QK8yTq.png)
- Click the `Agents` tab
- Click on the new `Roles` sub-tab
- Enter `Supreme Admin` as the name (or something similar)

![](https://safe.reku.me/o8kGnAjzkzm1.png)
- Next to the `Definition` tab, click on `Permissions`
- Check every box in `Tickets`, `Tasks`, and `Knowledgebase`

![](https://safe.reku.me/prcgqoZuX5AK.png)
- Click on `Add Role` at the bottom
- Repeat as you need (ideally only just enough)
- Next to the `Roles` sub-tab, click on `Departments`
- Enter `System Administrators` as the name (or similar)

![](https://safe.reku.me/RXB1jKZDMGq4.png)
- Click on `Create Dept` at the bottom
- Repeat as you need (ideally only just enough)
- Next to the `Roles` sub-tab, click on `Teams`
- Enter `Level II Support` as the name (or similar)

![](https://safe.reku.me/FiF6j501jB9M.png)
- Click on `Create Team` at the bottom
- Repeat as you need (ideally only just enough)
- Back to the top tabs, click on `Settings`
- Click on the new `Users` sub-tab
- (optional step) make sure `Require registration and login to create tickets` is unchecked

![](https://safe.reku.me/4Gbby9fMTMxb.png)
- Go back to the `Agents` tab
- Click on the new `Agents` sub-tab
- Fill out details, example details:

![](https://safe.reku.me/ChTQ1K5wZsM0.png)
- Next to `Username` click `Set Password`
- Set the password
- (optional) Uncheck `Send the agent a password reset email` and `Require password change at next login`

![](https://safe.reku.me/AqNR73nKrXn9.png)
- Click on `Set` at the bottom-right
- Next to the `Account` sub-sub-tab, click on `Access`
- Select the appropriate department and role (`System Administrators` and `Supreme Admin` here)

![](https://safe.reku.me/mdLtwBVlQpSQ.png)
- Click on `Save Changes` at the bottom
- To the right of `Access`, click on `Teams`
- Select the appropriate team (`Level II Support` here)

![](https://safe.reku.me/x5kKfvIfurpc.png)
- Click on `Save Changes` at the bottom
- Repeat as you need (ideally only just enough)
- Click on `Agent Panel` at the top right
- Click on the `Users` tab
- Click on `Add User`
- Fill out details, example details:

![](https://safe.reku.me/xquJ3PnecoIM.png)
- Click on `Add User` at the bottom-right
- Repeat as you need (ideally only just enough)
- Click on `Admin Panel` at the top right
- Click on the `Manage` tab
- Click on the new `SLA` sub-tab
- Fill out details, example details:

![](https://safe.reku.me/DZOY2uYyQy12.png)
- Click on `Add Plan` at the bottom
- Repeat as you need (ideally only just enough)
- To the left of `SLA`, click  on `Help Topics`
- Fill out details, example details:

![](https://safe.reku.me/2mfNt3exzJ3n.png)
- Repeat as you need (ideally only just enough)

You have finished the post installation configuration now.