# 💳 VaultX – Digital Bank

![VaultX Logo](https://img.shields.io/badge/VaultX-Digital%20Bank-1E90FF?style=for-the-badge&logo=databricks&logoColor=white)

[![Java Spring Boot CI](https://github.com/your-username/vaultx/actions/workflows/springboot-ci.yml/badge.svg)](https://github.com/your-username/vaultx/actions/workflows/springboot-ci.yml)
[![.NET Core CI](https://github.com/your-username/vaultx/actions/workflows/dotnet-ci.yml/badge.svg)](https://github.com/your-username/vaultx/actions/workflows/dotnet-ci.yml)
[![React Frontend CI](https://github.com/your-username/vaultx/actions/workflows/react-ci.yml/badge.svg)](https://github.com/your-username/vaultx/actions/workflows/react-ci.yml)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](./LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)]()
[![Tech](https://img.shields.io/badge/Tech-React%20%7C%20SpringBoot%20%7C%20.NET%20%7C%20MySQL-blue?style=for-the-badge)]()

---

## 📌 Introduction
**VaultX** is a secure, modern **online banking platform** designed to streamline the **customer onboarding process** through **real-time KYC (Know Your Customer)** verification.  

It supports **video KYC, document uploads, and secure transactions** with a **role-based access system** for Admins, Clerks, Managers, and Customers.  

---

## 🎯 Objectives
- ✅ Digitize end-to-end customer onboarding (PoI & PoA verification)  
- ✅ Secure, real-time **Video KYC using WebRTC**  
- ✅ Role-based access control for Admin, Clerk, Manager, and Customer  
- ✅ Manage accounts, transactions, and statements  
- ✅ Ensure **scalability, performance, and security**  

---

## ✨ Features
### 👤 Customer
- Register & upload **KYC documents** (PoI/PoA – Aadhaar, PAN, etc.)  
- Join **live Video KYC** session  
- View **account balance & transactions**  
- Download account statements as **PDF**  
- Perform **fund transfers**  

### 🧑‍💼 Clerk
- Access & review **pending KYC applications**  
- Conduct **Video KYC** via WebRTC  
- Capture **liveness checks & notes**  
- Forward application to Manager  

### 👨‍💼 Manager
- Approve/Reject **KYC applications**  
- Assign **account number & type**  
- Trigger **welcome email** with account details  

### 🛡️ Admin
- Manage staff accounts (Clerks, Managers)  
- View, edit, and delete customers  
- Monitor **active accounts & audit logs**  

---

## 🏗️ Tech Stack
- **Frontend:** React (Vite), Bootstrap  
- **Backend:**  
  - Spring Boot (Java)  
  - .NET Core  
- **Database:** MySQL / SQL Server  
- **Authentication:** JWT  
- **Real-time KYC:** WebRTC, STUN/TURN servers, WebSocket signaling  
- **Email Service:** SMTP-based  
- **Hosting:** Cloud-ready (AWS, Azure, GCP)  

---

## 📂 Project Structure
```bash
VaultX/
│── BankKycSystem.netBackend   # .NET Core Backend
│── bank-kyc-system            # Spring Boot Backend
│── vaultxfront                # React Frontend
