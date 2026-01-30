# ENTERPRISE AZ-104 ADMIN PROJECT

## Overview

This project demonstrates hands-on Azure Administrator (AZ-104) skills by designing, deploying, securing, monitoring, and cleaning up an enterprise-style Azure environment.

The focus of this project is on real-world Azure administration tasks such as networking, virtual machines, monitoring, backup, identity and access management (IAM), and cost control.

## Azure Services & Skills Covered

- Azure Resource Groups
- Virtual Networks (VNet) and Subnets
- Network Security Groups (NSG)
- Azure Virtual Machines (Linux)
- Public IP and Network Interfaces
- Azure Monitor and Alerts
- Recovery Services Vault (Backup)
- Azure Role-Based Access Control (RBAC)
- Cost Management and Resource Cleanup
- GitHub Documentation

### Architecture Explanation

User requests are sent from a web browser over HTTP (port 80) to the public IP address assigned to the Azure virtual machine.  
Network Security Group (NSG) rules control and restrict inbound traffic.  
The traffic flows through the Virtual Network and subnet to a Linux virtual machine running Nginx, which serves the web content.

## Architecture Diagram
User (Browser)
     |
     | HTTP (Port 80)
     v
Public IP Address
     |
     v
Network Security Group (NSG)
     |
     v
Virtual Network (VNet)
     |
     v
Subnet
     |
     v
Linux Virtual Machine (Ubuntu)
     |
     v
Nginx Web Server

## Project Implementation Phases

