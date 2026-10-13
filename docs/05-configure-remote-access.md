## Objective

The objective of this lab was to configure remote access to the Windows client virtual machine and allow authorized domain users to sign in remotely. I also used the Windows App to establish Remote Desktop connections to the Azure virtual machines, demonstrating remote administration in a cloud-hosted Active Directory environment.

## Implementation Steps

### Step 1: Enable Remote Desktop on the Client Computer

Accessed the Windows client computer’s system settings and enabled Remote Desktop to allow remote connections to the machine.

This configuration allows the client to accept Remote Desktop connections, subject to the applicable network, firewall, and user permission settings.

**Screenshot 1:** Enabling Remote Desktop on the Windows Client

### Step 2: Allow Domain Users to Access the Client

Configured the client computer’s remote access settings to allow authorized domain users to sign in remotely. This established the necessary user access permissions for remote connections to the client machine.

Remote access permissions must be granted to the appropriate users or groups, and users must have the necessary rights to sign in through Remote Desktop.

**Screenshot 2:** Configuring Remote Desktop User Permissions

### Step 3: Connect to the Azure Virtual Machines Using Windows App

Used the Windows App to initiate Remote Desktop connections to the Azure virtual machines. This provided a graphical interface for remotely accessing and managing the lab systems without needing to interact with them directly through the Azure portal.

**Screenshot 3:** Windows App Configured for Remote Connections

**Screenshot 4:** Successful Remote Desktop Session to a Virtual Machine
