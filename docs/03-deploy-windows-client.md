## Objective

The objective of this lab was to join the Windows client virtual machine to the `itlab.local` Active Directory domain hosted on Windows Server 2025. This established domain membership and prepared the client for centralized authentication, policy enforcement, and resource access.

## Implementation Steps

### Step 1: Join the Client Computer to the Domain

Used the existing Azure virtual network configuration to provide the client with network connectivity and DNS settings. Azure manages private IP address allocation for the virtual machine's network interface, so no manual network configuration was required on the client.

Joined the Windows client virtual machine to the `itlab.local` Active Directory domain by providing the necessary domain credentials.

**Screenshot 1:** Joining the Windows Client to the `itlab.local` Domain

### Step 2: Confirm Successful Domain Membership

After completing the domain join process, verified the successful join confirmation. This established the client as a member of the Active Directory domain and enabled it to participate in the domain environment.

**Screenshot 2:** Successful Domain Join Confirmation

## Verification and Results

Successfully joined the Windows client virtual machine to the `itlab.local` Active Directory domain using the existing Azure network configuration.

The client was now ready for subsequent labs involving domain user authentication, remote access, Group Policy configuration, and shared network resources.

## Skills Demonstrated

* Joining a Windows client to an Active Directory domain
* Understanding Azure virtual network integration
* Understanding Azure-managed private IP address allocation and DNS configuration
* Establishing domain membership
* Preparing a client workstation for centralized administration
