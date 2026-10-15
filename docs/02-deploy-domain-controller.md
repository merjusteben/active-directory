## Objective

The objective of this lab was to install Active Directory Domain Services (AD DS), promote the Windows Server 2025 virtual machine to a domain controller, and establish the `itlab.local` domain. DNS was configured as part of the domain controller deployment, and the Dynamic Host Configuration Protocol (DHCP) server role was installed to explore IP address management within the Azure-hosted lab environment.

## Implementation Steps

### Step 1: Install Active Directory Domain Services

> Installed the Active Directory Domain Services (AD DS) role on the Windows Server 2025 virtual machine. This role provides the services required to create and manage a centralized Windows domain, including domain user accounts, computer accounts, authentication, and directory objects.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/adds-install.png" alt="Azure Active Directory Project Overview" width="350">

### Step 2: Promote the Server to a Domain Controller

> Promoted the Windows Server 2025 virtual machine to a domain controller and created a new Active Directory domain named `itlab.local`.

> This established the domain infrastructure required for centralized identity management and domain-based authentication. The server became the primary domain controller for the lab environment.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/deploy-dc.png" alt="Azure Active Directory Project Overview" width="350">

### Step 3: Configure DNS Through Active Directory Deployment

> DNS was installed automatically during the Active Directory Domain Services configuration.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/deploy-dns.png" alt="Azure Active Directory Project Overview" width="350">

### Step 4: Install the DHCP Server Role

> Installed the Dynamic Host Configuration Protocol (DHCP) Server role to explore centralized IP address assignment for devices on the lab network.

> However, the DHCP server did not successfully lease IP addresses to client virtual machines in the Azure environment. Azure manages virtual network connectivity and private IP address allocation through its own infrastructure, which differs from a traditional on-premises network where a Windows DHCP server commonly assigns client addresses.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/deploy-dhcp.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/authorize-dhcp.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/dhcp-scope.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/dhcp-dns.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/dhcp-overview.png" alt="Azure Active Directory Project Overview" width="350">

