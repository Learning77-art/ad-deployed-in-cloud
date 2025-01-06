<p align="center">
  <img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# Deploying On-Premises Active Directory in Azure Cloud

This tutorial explains how to deploy and configure an on-premises Active Directory environment using Azure Virtual Machines.

---

## Video Demonstration

- ### [YouTube: How to Deploy On-Premises Active Directory within Azure Compute](https://www.youtube.com)

---

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services (AD DS)
- PowerShell

---

## Operating Systems

- Windows Server 2022
- Windows 10 (21H2)

---

## Deployment
1. Set up Azure resources (resource groups, virtual network, and subnets).
2. Deploy virtual machines (Domain Controller and Client).
3. Configure Active Directory Domain Services.
4. Join the client machine to the Active Directory domain.

---

## Configuration Steps

### Step 1: Create Azure Resources

1. Create a Resource Group in Azure.
2. Set up a Virtual Network (VNet) with a subnet.

### Step 2: Deploy Virtual Machines

1. Deploy a Windows Server 2022 VM to act as the Domain Controller.
2. Deploy a Windows 10 VM for testing and domain connection.

### Step 3: Configure Active Directory Domain Services (AD DS)

1. Install the AD DS role on the Windows Server 2022 VM.
2. Promote the server to a Domain Controller.
3. Configure DNS to resolve domain names.

### Step 4: Join the Client Machine to the Domain

1. Update DNS settings on the client machine to point to the Domain Controller.
2. Join the client machine to the domain.
3. Test functionality by logging in with domain credentials.

---

<p align="center">
  <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Deployment Diagram"/>
</p>

---

## Additional Notes

- The project demonstrates a simulated on-premises environment in Azure for educational purposes.
- Follow security best practices when setting up your environment.
