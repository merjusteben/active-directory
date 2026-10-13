## Objective

This lab involved creating a resource group, configuring a virtual network and subnet, setting up custom DNS, and deploying the Windows Server 2025 domain controller virtual machine and Windows client virtual machine on Azure.

## Implementation Steps

### Step 1: Create the Azure Resource Group

> Created a resource group named `IT-Lab-RG` to organize and manage the Azure resources associated with the Active Directory lab. This resource group serves as the central container for the infrastructure deployed throughout the project.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/01-resource-group.png" alt="Azure Active Directory Project Overview" width="350">

### Step 2: Configure the Virtual Network and Subnet

> Created a virtual network named `IT-Lab-Vnet` to provide network connectivity between the virtual machines in the lab. Configured the virtual network with an address space of `/16` and created a subnet named `IT-Lab-Subnet` with a `/24` address range.

> This network configuration provides a dedicated private network for communication between the domain controller and the Windows client.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/vnet.png" alt="Azure Active Directory Project Overview" width="350">

### Step 3: Configure Custom DNS Settings

> Configured custom DNS settings for the virtual network to support name resolution within the Active Directory environment. This configuration establishes the DNS settings that the virtual machines use to locate domain services and resolve internal hostnames.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/dns.png" alt="Azure Active Directory Project Overview" width="350">

### Step 4: Deploy the Windows Server 2025 Virtual Machine

> Created a Windows Server 2025 virtual machine to serve as the foundation for the Active Directory domain controller. Configured a static private IP address and aligned its DNS settings with the custom DNS configuration used in the lab.

> This server will host the Active Directory Domain Services role and provide centralized identity and domain management after the domain controller configuration is completed in Lab 02.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/server-25.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/02-server-25.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/ip-config.png" alt="Azure Active Directory Project Overview" width="350">

### Step 5: Deploy the Windows Client Virtual Machine

> Created a separate Windows client virtual machine within the lab environment. This client will be used to test domain joining, domain user authentication, remote access, Group Policy application, and access to shared network resources in subsequent labs.

<img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/01-win-11.png" alt="Azure Active Directory Project Overview" width="350"> <img src="https://github.com/merjusteben/active-directory/blob/main/screenshots/02-win-11.png" alt="Azure Active Directory Project Overview" width="350">
