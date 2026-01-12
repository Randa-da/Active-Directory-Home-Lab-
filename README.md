# Active-Directory-Home-Lab

This folder contains step-by-step documentation for building and configuring
an Active Directory Home Lab using Windows Server 2022 and Windows 10.

Each document focuses on a specific service or configuration.

## Active Directory Setup
- [Active Directory Domain Services (AD DS)](ad-ds.md)  
  Installation and domain creation process.

## Server & Client Configuration
- [Server and Client Setup](server-client-setup)  
  Initial configuration of Windows Server and Windows 10 client,
  including domain join and connectivity validation.

## Network Services
- [DHCP Configuration](dhcp.md)  
  Internal IP address allocation for domain clients.
- [NAT Configuration (RRAS)](NAT-Config.md)  
  Internet access for internal network using Routing and Remote Access.


## Automation
- [Create Active Directory Users (PowerShell)](create_AD_users_PowerShell)  
  PowerShell script used to automate domain user creation.


## Validation & Testing
Configuration was validated using:
- `ipconfig` on client machines
- Successful domain join
- Internet connectivity through NAT
