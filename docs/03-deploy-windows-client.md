## Objective

The objective of this lab was to join the Windows client virtual machine to the `itlab.local` Active Directory domain. This established the connection between the client computer and the domain controller, enabling centralized authentication and domain-based management.

## Implementation Steps

### Step 1: Configure the Client's Network Settings

> Verified the Windows client virtual machine's network configuration to ensure it could communicate with the domain controller. The client needed access to the domain controller's DNS service to locate the `itlab.local` domain.

**Screenshot 1:** Windows Client Network Configuration

### Step 2: Join the Client Computer to the Domain

> Joined the Windows client virtual machine to the Active Directory domain named `itlab.local`.

**Screenshot 2:** Joining the Windows Client to `itlab.local`

**Screenshot 3:** Successful Domain Join Confirmation

### Step 3: Verify Domain Membership

> Verified that the Windows client was joined to the `itlab.local` domain. This established the foundation for centralized management through Active Directory and prepared the client for subsequent configuration and testing.

**Screenshot 4:** Windows Client Showing Domain Membership
