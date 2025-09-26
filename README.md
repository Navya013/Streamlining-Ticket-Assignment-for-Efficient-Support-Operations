# 🚀 Streamlining Ticket Assignment for Efficient Support Operations

![ServiceNow](https://img.shields.io/badge/Platform-ServiceNow-blue) ![Status](https://img.shields.io/badge/Status-Completed-green) ![Author](https://img.shields.io/badge/Author-Navyasri_Rajanala-orange)

---

## Table of Contents
- [🌟 Project Overview](#-project-overview)
- [🛠 Key Features](#-key-features)
- [📂 Project Modules](#-project-modules)
- [⚡ Technologies Used](#-technologies-used)
- [📝 Setup Instructions](#-setup-instructions)
- [🎯 Benefits](#-benefits)
- [✅ Project Status](#-project-status)
- [📌 Conclusion](#-conclusion)
- [👤 Author](#-author)

---

## 🌟 Project Overview
The objective of this initiative is to implement an automated system for ticket routing at **ABC Corporation**, aimed at improving operational efficiency by accurately assigning support tickets to the appropriate teams. This solution reduces delays in issue resolution, enhances customer satisfaction, and optimizes resource utilization within the support department. By leveraging ServiceNow workflows, roles, tables, ACLs, and Flow Designer automation, tickets are routed efficiently based on issue type, priority, and team expertise.

---

## 🛠 Key Features
- ✅ Automated Ticket Routing to appropriate teams  
- ✅ Conditional Logic based on ticket type and priority  
- ✅ Role-Based Assignment ensuring authorized access  
- ✅ Real-Time Notifications & Alerts for requesters and support teams  
- ✅ Reporting & Analytics to track resolution times and SLA adherence  
- ✅ End-User Testing to ensure portal and workflow functionality  

---

## 📂 Project Modules

### 1️⃣ User, Group & Role Management
- Created users and verified details  
- Configured operational and platform groups  
- Assigned roles to users and groups  

### 2️⃣ Tables & Data Management
- Created **Operations Related** table with dynamic columns  
- Configured field properties (mandatory, read-only, default values)  
- Added choices for issue types:  
  - Unable to login to platform  
  - 404 Error  
  - Regarding Certificates  
  - User Expired  

### 3️⃣ Access Control (ACL)
- Configured ACLs to manage read/write access  
- Assigned Admin, Platform, and Certificate roles for operations  

### 4️⃣ Flow Designer Automation
- Created flows for automated ticket assignment to **Certificates** or **Platform** groups  
- Configured triggers, conditions, and actions  
- Tested end-to-end flows for reliability  

### 5️⃣ Notifications & Alerts
- Automated email notifications and alerts for ticket assignments  
- Configured escalation rules for SLA compliance  

### 6️⃣ End-User Testing
- Verified Service Portal workflow  
- Checked notifications, approvals, and ticket assignments  
- Ensured seamless user experience  

---

## ⚡ Technologies Used
- **ServiceNow Platform:** Users, Groups, Roles, Tables, ACLs, Flow Designer  
- **Email & Notification System:** Automated alerts and notifications  
- Optional: Integration with external ITSM tools  

---

## 📝 Setup Instructions
1. Access your **ServiceNow** development instance  
2. Create users, groups, and roles according to operational requirements  
3. Create tables for ticket tracking with appropriate columns and choices  
4. Configure ACLs for sensitive fields  
5. Design and implement flows in **Flow Designer** for automated ticket routing  
6. Test the end-to-end workflow in the Service Portal  
7. Monitor ticket assignments, notifications, and SLA adherence  

---

## 🎯 Benefits
- Reduces manual effort in managing support tickets  
- Ensures accurate role-based access and ticket assignment  
- Automates ticket routing based on issue type and priority  
- Improves SLA compliance and customer satisfaction  
- Provides real-time visibility and reporting on support operations  

---

## ✅ Project Status
- [x] User, Group & Role Management  
- [x] Table & Field Management  
- [x] ACL Configuration  
- [x] Flow Designer Automation  
- [x] Notifications & Alerts  
- [x] End-User Testing  

---

## 📌 Conclusion
The implementation of the automated ticket routing system at **ABC Corporation** has been a significant success. Leveraging ServiceNow, the process of assigning support tickets has been streamlined, addressing the challenges of manual routing and ensuring timely resolution of issues. This solution enhances operational efficiency, reduces delays, and improves overall customer satisfaction.

---

## 👤 Author
**Navyasri Rajanala**  
GitHub: [https://github.com/Navya013](https://github.com/Navya013)  
Contact: 322103310192@gvpce.ac.in
