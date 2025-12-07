# Azure Linux Nginx Web Server

This project demonstrates how I deployed a secure Ubuntu Linux Virtual Machine with Nginx web server on Microsoft Azure.

## 🎯 Objective
- Deploy a Linux VM on Azure
- Secure the VM using Network Security Group (NSG)
- Install and configure Nginx
- Host a custom website
- Access the website using a public IP

## 🏗️ Architecture
- Azure Resource Group
- Virtual Network & Subnet
- Network Security Group (NSG)
- Ubuntu Linux Virtual Machine
- Public IP Address
- Nginx Web Server

## 🔐 Security Configuration
- SSH (Port 22): Allowed only from my public IP
- HTTP (Port 80): Allowed from anywhere

## 🛠️ Technologies Used
- Microsoft Azure
- Azure Virtual Machines
- Azure Virtual Network
- Network Security Groups (NSG)
- Ubuntu Linux
- Nginx
- SSH

## ✅ Steps Performed
1. Created Resource Group
2. Created VNet & Subnet
3. Created NSG and inbound security rules
4. Deployed Ubuntu Linux VM
5. Connected to VM using SSH
6. Installed and configured Nginx
7. Deployed a custom HTML website
8. Verified website access using public IP

## 📸 Screenshots
Screenshots are available in the `screenshots` folder:
- VM Overview
- NSG Rules
- SSH Connection
- Nginx Status
- Website Live

## 🏁 Result
Successfully deployed a secure and publicly accessible Linux web server on Microsoft Azure.

---

👤 **Created by:** Raghu (Cloud96)
