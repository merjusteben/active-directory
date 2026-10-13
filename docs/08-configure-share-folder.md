## Objective

The objective of this lab was to configure a shared folder for the Sales department and implement permission-based access to shared resources within the `itlab.local` Active Directory domain. I created a Sales shared folder, assigned specific permissions to designated users, and used Group Policy to map the shared folder as a network drive on users' computers.

This setup demonstrates centralized file sharing, access control, and automated network drive deployment in an Active Directory environment.

## Implementation Steps

### Step 1: Create the Sales Shared Folder

Created a shared folder named `Sales` to provide a centralized location for departmental files. The folder was configured as a network resource so authorized domain users could access it from their computers.

**Screenshot 1:** Sales Shared Folder Configuration

### Step 2: Configure Folder Permissions

Assigned specific permissions to designated users to control access to the Sales shared folder. These permissions determine which actions users can perform, such as viewing, reading, modifying, or managing files, based on the rights granted.

This approach supports controlled access to departmental resources and helps ensure that users can perform only the activities permitted by their assigned permissions.

**Screenshot 2:** Sales Folder Permissions

**Screenshot 3:** User or Group Permission Assignments

### Step 3: Configure Network Drive Mapping Through Group Policy

Used Group Policy Management to configure a mapped network drive pointing to the Sales shared folder. This allows the shared resource to appear automatically in File Explorer on users' computers when the applicable Group Policy settings are processed.

The mapped drive provides a convenient way for authorized users to access shared files without manually entering the network path each time.

**Screenshot 4:** Group Policy Drive Mapping Configuration

### Step 4: Access the Mapped Drive from a Client Computer

Signed in to a domain-joined client computer and accessed the mapped network drive through File Explorer. Users who have the necessary permissions can browse the shared folder and perform actions allowed by their assigned access rights.

This demonstrates how Group Policy can simplify access to shared resources while the folder permissions continue to control what users are authorized to do.

**Screenshot 5:** Sales Network Drive Displayed in File Explorer

**Screenshot 6:** Access to the Sales Shared Folder from a Client Computer
