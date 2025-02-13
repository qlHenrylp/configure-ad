<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- **Create an Azure Virtual Network and Subnet**  
- **Deploy Virtual Machines (Domain Controller & Client PC)**  
- **Configure Active Directory Domain Services (AD DS)**  
-  **Join Client PC to Active Directory Domain**  

<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/86775fd5-040e-4494-8ca3-84b675f12cc1)

Before deploying Active Directory, we need to create an Azure Virtual Network to ensure all virtual machines can communicate. This network will contain a subnet where the Domain Controller and Client PC will be placed.
</p>
<br />

![image](https://github.com/user-attachments/assets/47aaf4d1-1eca-4cdf-9b44-320a6dac7035)

After setting up the Virtual Network and deploying the Domain Controller, we install and configure Active Directory Domain Services (AD DS) to enable user authentication and management.
</p>
<br />
