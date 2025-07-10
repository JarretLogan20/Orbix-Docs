# 4.2 System Administration (The Admin Panel)

The **Admin Panel** is the central hub for system administrators to manage the Orbix environment for their organization. Within this panel, administrators handle user accounts, manage system-wide permissions and roles, and configure project templates and data ingestion settings.

## 4.2.1 Accessing the Admin Panel

Access to the **Admin Panel** is restricted to users with specific permissions.

1.  To access the panel, your user account must have **Staff Status** permission enabled.
2.  If you have the correct permission, click on your profile at the bottom of the main navigation menu.
3.  Select **Admin Panel** from the menu options that appear. You will then be directed to the **Admin Panel** dashboard.

![orbix-navigation-admin-panel](../assets/orbix-navigation-admin-panel.png){: style="height: 300px"}

[Screenshot: The main navigation menu with the user profile clicked, showing the "Admin Panel" option.]

## 4.2.2 Managing Users & Permissions

From the **Admin Panel** dashboard, administrators can create and manage all user accounts and their associated access levels.

**Creating New User Accounts**

1.  From the **Admin Panel** dashboard, locate the **Users** section and click the **Add** button.
2.  The **Add User** form will open. Enter the new user's information:
    * **Username** (Required; used for signing in)
    * **Email Address** (Required)
    * **Name of User** (Required)
    * **Phone Number** (Optional)
3.  Click the **Save and Continue** button. This creates the user's account and immediately takes you to the permissions tab to configure their access.

After creating the user, you must assign the necessary permissions.

1.  In the **Permissions** tab for the new user, you can configure their system-wide access. Key permissions include:
    * **Active**: Designates whether this user should be treated as active within Orbix. Inactive users do not appear in system processes.
    * **Staff Status**: Grants the user access to the **Admin Panel**.
    * **Superuser Status**: Grants the user all permissions without needing to assign them individually.
2.  You can also assign users to pre-defined permission groups (e.g., **Technician**, **Auditor**, **Manager**) or assign specific, individual actions.
3.  After configuring the user's permissions, you must click the **Email login details** button on their profile. This sends an email to the user with a link to finish setting up their account and create a password.

![orbix-permissions-panel](../assets/orbix-permissions-panel.png){: style="height: 300px"}

[Screenshot: The user permissions tab within the Admin Panel, showing the Active, Staff Status, and Superuser checkboxes.]

**Assigning System-Wide Roles and Permissions**

Administrators can create standardized roles to apply a set of permissions to multiple users quickly.

1.  From the **Admin Panel** dashboard, navigate to the **Roles** (or Groups) section and click the **Add** button.
2.  In the **Add Role** form, enter a name for the role (e.g., Technician) and select all the permissions that users with this role should have.
3.  Click **Save** to create the role. Now you can assign this role to any user.
4.  To manage existing roles, click the **Manage** button in the **Roles** section. The **Roles Dashboard** allows you to edit permissions, rename, or delete any custom role.

![orbix-roles-panel](../assets/orbix-roles-panel.png){: style="height: 300px"}

**Deactivating or Deleting Users**

When a user no longer requires access to Orbix, an administrator can either deactivate or permanently delete their account. This is done from the **Permissions** tab on the user's page.

* **To Deactivate a User**: Uncheck the **Active** checkbox. This action makes the user inactive, preventing them from appearing in any Orbix processes. It does not delete their account, and their status can be changed back to active at any time.
* **To Delete a User**: Scroll to the bottom of the user's page and click the **Delete** button. This action is permanent and will completely remove the user and their credentials from the system.

## Configuring Project Templates & Data Ingestion

