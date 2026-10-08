# AWS-Windows-VPN-Private-EC2
# Windows Server VPN & Private EC2 Connectivity – AWS

## Project Overview
Implemented a Windows Server-based VPN environment on AWS to establish VPN connectivity from a Windows laptop and access a private Windows EC2 instance through RDP.

## Technologies Used
- AWS EC2
- AWS VPC
- Public & Private Subnets
- Security Groups
- Route Tables
- Windows Server
- RRAS (Routing and Remote Access Service)
- PPTP VPN
- NAT
- RDP

## What I Implemented
- Created a VPC with public and private subnets
- Deployed a public Windows EC2 instance as the VPN/RRAS server
- Deployed a private Windows EC2 instance without a public IP
- Configured RRAS and PPTP VPN on the Windows Server
- Configured VPN address pool, user access and NAT
- Configured Security Group rules for VPN and RDP connectivity
- Established VPN connectivity from a Windows laptop
- Verified access to the private Windows EC2 instance through RDP

## Documentation
The complete step-by-step implementation with screenshots is available in the PDF:
`VPN_Server_on_Windows_EC2.pdf`
