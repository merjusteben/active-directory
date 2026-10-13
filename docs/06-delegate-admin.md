## Objective

The objective of this lab was to implement delegated administration in Active Directory by assigning limited administrative permissions to the Help Desk group within specific Organizational Units (OUs). The goal was to allow Help Desk personnel to perform routine user management tasks, such as creating user accounts and resetting passwords, without granting them full administrative access to the domain.

## Implementation Steps

### Step 1: Select the Target Organizational Unit

Opened Active Directory Users and Computers (ADUC) and selected the IT Organizational Unit as the target for delegated permissions.

Delegating permissions at the OU level allows administrative tasks to be assigned within a specific organizational boundary rather than granting unrestricted access across the entire domain.

**Screenshot 1:** Selecting the IT Organizational Unit in Active Directory Users and Computers

### Step 2: Configure Delegation of Control

Used the Delegation of Control Wizard to assign specific administrative permissions to the Help Desk security group.

Selected the Help Desk group as the delegated administrative group and configured permissions for designated user management tasks within the IT Organizational Unit.

**Screenshot 2:** Selecting the Help Desk Group in the Delegation of Control Wizard

### Step 3: Assign Limited User Management Permissions

Configured the Help Desk group to perform selected administrative tasks, including:

* **Create user accounts:** Allow Help Desk personnel to create user accounts within the delegated Organizational Unit.
* **Reset user passwords:** Allow Help Desk personnel to reset passwords for applicable user accounts within the delegated scope.

These permissions enable the Help Desk group to handle common support requests while limiting its administrative responsibilities to the tasks explicitly delegated.

**Screenshot 3:** Selecting Delegated User Management Tasks

**Screenshot 4:** Reviewing or Completing the Delegation Configuration
