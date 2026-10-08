# Lab 1: Azure setup

## Goal
Build the Azure foundation for the lab: a resource group, a virtual network with a subnet, and two VMs (Windows Server and a Windows 11 client).

## Steps

### 1. Create the resource group
Searched for **Resource groups** in Azure, selected **Create**, chose my subscription, named it `[resource-group-name]`, picked the region `[region]`, and created it.

![Resource group created](../screenshots/01-resource-group.png)

### 2. Create the virtual network
Searched for **Virtual networks** and selected **Create**. Chose the subscription and resource group, named the network `[vnet-name]`, and picked the same region. The address space is `[x.x.0.0/16]`.

![Virtual network created](../screenshots/02-virtual-network.png)

### 3. Add a subnet
Inside the virtual network, I created a subnet named `[subnet-name]` with the range `[x.x.x.0/24]`.

![Subnet created](../screenshots/03-subnet.png)

### 4. Set a custom DNS server
In the virtual network's DNS settings, I selected **Custom** and entered the IP address I planned to give the Windows Server. The domain controller will run DNS, so the whole network needs to point to it.

![Custom DNS configured](../screenshots/04-custom-dns.png)

### 5. Create the Windows Server VM
Searched for **Virtual machines**, selected **Create**, and chose Windows Server 2022. I set the private IP to **static** and used the same address I entered as the custom DNS server.

![Windows Server VM created](../screenshots/05-server-vm.png)
![Static IP configured](../screenshots/06-server-static-ip.png)

### 6. Create the Windows 11 client VM
I repeated the same VM steps for the client, placing it in the same virtual network and subnet.

![Windows 11 client VM created](../screenshots/07-client-vm.png)

## Result
The environment is ready for Active Directory: both VMs are in one network, and DNS points to the future domain controller.

## What I learned
- The DNS server address must be decided before the domain controller exists.
- A static IP keeps the domain controller's address from changing.
