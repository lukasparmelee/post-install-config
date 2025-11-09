<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" width="300"/>
</p>

# osTicket - Post-Install Configuration

This tutorial outlines the **post-installation configuration** of the open-source help desk ticketing system **osTicket**, focusing on administrative setup, roles, departments, and ticket workflow management.

---

## 🎥 Video Demonstration

- [YouTube: How To Configure osTicket, Post-Installation](https://www.youtube.com)

---

## 🧰 Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)
- osTicket Web Interface

---

## 💻 Operating System Used
- Windows 10 (21H2)

---

## ⚙️ Post-Install Configuration Objectives

1. Configure system settings and admin panel
2. Set up roles, departments, and teams
3. Create and assign user accounts and permissions
4. Configure help topics and ticket workflows
5. Verify email piping and test ticket creation

---

## 🧩 Configuration Steps

### Step 1: Access the Admin Panel
<p align="center">
  <img src="./postinstall-1.png" width="80%" alt="osTicket Admin Panel"/>
</p>

After installation, navigate to the Admin Panel by logging in as the system administrator. Verify that the installation was successful and review the system settings for accuracy (site name, URL, and default email).

---

### Step 2: Configure Roles and Departments
<p align="center">
  <img src="./postinstall-2.png" width="80%" alt="osTicket Roles and Departments"/>
</p>

Create new **roles** (e.g., Help Desk Agent, Supervisor) and **departments** (e.g., IT Support, Customer Service). Roles determine permissions, while departments organize incoming tickets by category.

---

### Step 3: Add Teams and Agents
<p align="center">
  <img src="./postinstall-3.png" width="80%" alt="osTicket Teams and Agents"/>
</p>

Assign agents to specific departments or teams to define who handles different types of tickets. Ensure that each agent has the correct access level for their responsibilities.

---

### Step 4: Configure Help Topics and Ticket Settings
<p align="center">
  <img src="./postinstall-4.png" width="80%" alt="osTicket Help Topics"/>
</p>

Create **Help Topics** to categorize ticket submissions (e.g., “Password Reset,” “Network Issue”). This improves routing and response efficiency.

---

### Step 5: Configure Email Settings and Test Ticket Creation
<p align="center">
  <img src="./postinstall-5.png" width="80%" alt="osTicket Email and Tickets"/>
</p>

Set up system email addresses for ticket creation and notifications. Test ticket creation and assignment to verify the configuration works properly.

---

## 🧾 About

This project demonstrates the **post-installation configuration** of osTicket in a Windows environment. The process reinforces concepts of **user management**, **departmental organization**, and **ticket routing**, essential skills in **IT service desk operations**.

**Skills Demonstrated:**
- osTicket Administrative Configuration  
- Role and Department Setup  
- Ticket Routing and Workflow Management  
- System Email Configuration  
- Azure VM and IIS Management  

---
