## Objective

The objective of this lab was to join the Windows client virtual machine to the `itlab.local` Active Directory domain hosted on Windows Server 2025. This established domain membership and prepared the client for centralized authentication, policy enforcement, and resource access.

## Implementation Steps

### Step 1: Join the Client Computer to the Domain

> Used the existing Azure virtual network configuration to provide the client with network connectivity and DNS settings. Azure manages private IP address allocation for the virtual machine's network interface, so no manual network configuration was required on the client.

> Joined the Windows client virtual machine to the `itlab.local` Active Directory domain by providing the necessary domain credentials.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/win11-joined.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/win11-joined2.png" alt="Azure Active Directory Project Overview" width="350">
