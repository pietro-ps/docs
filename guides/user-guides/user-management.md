# User Management

The purpose of this document is to demonstrate how to perform some management actions on Rocket.Chat users. 
This guide assumes that the administrator has already completed the installation and basic configuration of your Rocket.Chat server.

After starting your Rocket.Chat instance and logging in, you will see the system home screen.

<p align="center">
  <img src="img/HomeScreen.png" height="400">
</p>

To access the administrative area, click on the **options [![](img/BtnOptions.png)]** button and select the “Administration” option.

<p align="center">
  <img src="img/HomeScreenAdminOpt.png">
</p>

The home page of the administrative area will be displayed, as shown in the screenshot below:

<p align="center">
  <img src="img/AdminArea.png" height="400">
</p>

To access the users panel, in the menu on the left, click the **Users [![](img/BtnUsers.png)]** button, the following screen will be displayed:

<p align="center">
  <img src="img/AdminAreaUsers.png" height="400">
</p>

In this guide, we will check:

- [How to create a new user](#creating-a-new-user);
- [How to reset a user password](#reseting-passwords);
- [How to disable users](#disabling-users);
- [How to enable users](#enabling-users);
- [How to remove users](#removing-users);
- [How to change a user role](#changing-users-roles).

Next we will analyze how to carry out the mentioned procedures.

## Creating a new user

In Rocket.Chat it is possible to add users directly through the users administration panel or by inviting them. In this guide we will exemplify how to perform this first operation, click on the **[![](img/BtnNew.png)]** button, the menu for adding users will be displayed on the right.

<p align="center">
  <img src="img/AdminAreaUsersAdd.png" height="400">
</p>

Complete the form as exemplified:

- **Name:** Enter the user name. Ex.: user; 
- **Username:** Enter the user login credentials. Ex.: userlogin;
- **Email:** Inform the user email address. Ex.: user@rocketchat.com;
- **Verified [![](img/BtnEnabled.png)]:**  If this option is active, this user will already be verified without needing to confirm via a verification email;
- **Status message:** Defines a personalized message that appears in the status field in the user profile;
- **Bio:** In this field it is possible to write a short biography about the user that will appear in the status field in the user profile;
- **Password:** Enter the password that the user should use to log in;
- **Require password change [![](img/BtnEnabled.png)]:** If active, this option will determine that the user will be required to change his password at the next login;
- **Set random password and send by email [![](img/BtnEnabled.png)]:** If active, this option will determine that the user will receive a randomly generated password in the registered email;
- **Roles:** Defines the role of the user, roles are used to define the level of access in the system;
- **Join default channels [![](img/BtnEnabled.png)]:** Determines whether this user will automatically be inserted into standard channels;
- **Send welcome email [![](img/BtnEnabled.png)]:** If active, this option will send a welcome message to the registered email.

If you want to close this window click on the **[![](img/BtnCancel.png)]** button, but if you prefer to save this information and create the user click on the **[![](img/btnSave.png)]** button.

<p align="center">
  <img src="img/AddUser.png" height="400">
</p>
 
The created user will be displayed on the panel, as shown below:

<p align="center">
  <img src="img/AdminAreaUsersAdded.png" height="400">
</p>
 
Next, we will look at how to reset a user password.

## Reseting passwords

To reset a user password, select it, more information about it will be displayed in a menu on the right side of the screen.

<p align="center">
  <img src="img/AdminAreaUsersAdded.png" height="400">
</p>

Click the **[![](img/btnEdit.png)]** button, the menu with the information that has been added to the user profile will be displayed.

<p align="center">
  <img src="img/EditUsers.png" height="400">
</p>

To reset the password, simply activate the option **Require password change [![](img/BtnEnabled.png)]** so that the user is required to change their own password at the next login.
Finally, click the **[![](img/btnSave.png)]** button to make changes.

Next, we will look at how to disable a user.

## Disabling users

To disable a particular user, select it, more information about it will be displayed in a menu on the right side of the screen.

<p align="center">
  <img src="img/AdminAreaUsersUserInfo.png" height="400">
</p>

Click on the **[![](img/BtnOptionsLight.png)]** button, a menu with some options will be displayed, to disable a user click on the **[![](img/BtnDeactivate.png)]** option, as shown below:

<p align="center">
  <img src="img/OptDeactivate.png">
</p>

Next, we will look at how to enable a user.

## Enabling users

To enable a particular user, select them, more information about it will be displayed in a menu on the right side of the screen.

<p align="center">
  <img src="img/AdminAreaUsersUserInfo.png" height="400">
</p>

Click on the **[![](img/BtnOptionsLight.png)]** button, a menu with some options will be displayed, to enable a user click on the **[![](img/BtnActivate.png)]** option, as shown below:

<p align="center">
  <img src="img/OptActivate.png">
</p>

Next, we will look at how to remove a user.

**Removing users**

To remove a particular user, select them, more information about it will be displayed in a menu on the right side of the screen.

<p align="center">
  <img src="img/AdminAreaUsersUserInfo.png" height="400">
</p>

Click on the **[![](img/BtnOptionsLight.png)]** button, a menu with some options will be displayed, to remove a user click on the **[![](img/BtnDelete.png)]** option, as shown below:

<p align="center">
  <img src="img/OptDelete.png">
</p>

An alert message will be displayed to confirm the user deletion. Note that after performing this action, the user will be permanently deleted.

<p align="center">
  <img src="img/AreYouSureMsg.png">
</p>

If you want to close this window and do not remove the user, click the **[![](img/BtnCancel.png)]** button. However, if you are sure that you want to remove the user click on the **[![](img/BtnDelete2.png)]** button, the user will be deleted and the notification below will be displayed.

<p align="center">
  <img src="img/DeletedMsg.png">
</p>

To close this window, just click the **[![](img/BtnOk.png)]** or **[ ![](img/BtnX.png)]** button.

Next, we will look at how to change a user role.

## Changing users roles

Roles are used to define which system resources the user will have access, for more information about roles, check this [page](https://docs.rocket.chat/guides/administrator-guides/permissions#roles).
To change roles, select the desired user, more information about the profile selected will be displayed in a menu on the right side of the screen.

<p align="center">
  <img src="img/AdminAreaUsersUserInfo.png" height="400">
</p>

Click the **[![](img/btnEdit.png)]** button, the menu with the information that has been added to the user's profile will be displayed.

<p align="center">
  <img src="img/EditUsers.png" height="400">
</p>

To change the roles linked to a user, access the **Roles** combobox and select the desired option. In this example we will give the user administrative powers, for that we will select **"Admin"**.

<p align="center">
  <img src="img/Roles.png">
</p>

Finally, click the **[![](img/btnSave.png)]** button to make changes.

After saving, the role will be displayed in the user profile, as shown in the screenshot below the **"Role"** field.

<p align="center">
  <img src="img/UsersInfoRoles.png" height="400">
</p>

This concludes the scope of this guide, for more information about Rocket.Chat and to have access to more documentation, visit https://docs.rocket.chat/.
