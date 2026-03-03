# -Core-Azure-Networking-Lab
 completed a full Core Azure Networking Lab in Microsoft Azure to practice real cloud networking architecture.
This lab helped me understand how to design, secure, and connect resources inside a Virtual Network using Azure-native tools.

🔹 What I built
A Virtual Network with proper subnet segmentation

WebSubnet and AppSubnet, each with its own:

Virtual Machine

Network Interface (NIC)

Network Security Group (NSG)

Application Security Group (ASG)

A dedicated AzureBastionSubnet for secure RDP/SSH access

ASG-to-ASG NSG rules to control traffic between tiers

Port 80 communication from Web → App

No public IPs on VMs — all access through Azure Bastion
