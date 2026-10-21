## Objective

> The objective of this lab was to implement delegated administration in Active Directory by assigning limited administrative permissions to the Help Desk group within specific Organizational Units (OUs). The goal was to allow Help Desk personnel to perform routine user management tasks, such as creating user accounts and resetting passwords, without granting them full administrative access to the domain.

## Implementation Steps

### Step 1: Select the Target Organizational Unit

> Opened Active Directory Users and Computers (ADUC) and selected the IT Organizational Unit as the target for delegated permissions.

> Delegating permissions at the OU level allows administrative tasks to be assigned within a specific organizational boundary rather than granting unrestricted access across the entire domain.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/delegation.png" alt="Azure Active Directory Project Overview" width="350">

### Step 2: Configure Delegation of Control

Used the Delegation of Control Wizard to assign specific administrative permissions to the Help Desk security group.

Selected the Help Desk group as the delegated administrative group and configured permissions for designated user management tasks within the IT Organizational Unit.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/delegation2.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/delegation3.png" alt="Azure Active Directory Project Overview" width="350">
