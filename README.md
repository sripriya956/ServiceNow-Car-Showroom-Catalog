🚗 Mahendra Car Showroom – ServiceNow Service Catalog Project

Mahendra Car Showroom is a ServiceNow-based Service Catalog automation project developed to streamline car booking, approvals, task fulfillment, and notification management.
Built using ServiceNow ITSM platform, this project demonstrates catalog management, workflow automation, multi-level approvals, and service portal integration.

🚀 Features
👤 User Features:
Browse car models in Service Portal
Order cars directly from catalog
Automatic request number generation
Email notification on approval/rejection
Delivery tracking via task system
🛠 Admin Features
Create and manage catalog items
Configure pricing and categories
Multi-level approval workflow
Create custom fulfillment tasks
Send automated email notifications
Manage users, roles, and groups
🎯 Core Functionalities
Service Catalog Creation (Mahendra)
Categories: Sudden, XUV, Sports
Catalog Items:
Volkswagen Polo
Mahindra Thar
Mahindra XUV700
Multi-level Approval (Sales → Supervisor)
Task Automation (Car Production & Fulfillment)
Custom Table: Cars Fulfillment
Email Notifications (Approved / Rejected)
Service Portal Testing
🧰 Tech Stack
Platform: ServiceNow
Modules Used:
Service Catalog
Workflow Editor / Flow Designer
System Security (Users, Roles, Groups)
System Definition (Tables)
Notifications (HTML Email)
Service Portal
Version Control: Git & GitHub
📁 Project Structure
Copy code

Mahendra-Car-Showroom/
│
├── README.md
├── Car_Showroom_Update_Set.xml
├── booking_notification.html
├── screenshots/
│   ├── catalog.png
│   ├── workflow.png
│   ├── approvals.png
│   ├── service_portal.png

🔄 Workflow Process
User orders car from Service Portal
Request created (sc_req_item)
Sales Approval
Supervisor Approval
Car Production Task created
Car Fulfillment Task created
Email Notification sent
Task closed (Complete / Incomplete)
🔐 Security Configuration
Custom Role: emp1
User: Sales Person
Group: Showroom
Role-based approval access
Task-level control
🧪 Testing
Testing methods used:
Manual testing in Service Portal
Approval testing
Task validation
Email notification testing
Workflow execution tracking 
📊 Results
✔ Catalog items visible in portal
✔ Requests generate automatically
✔ Multi-level approvals work
✔ Tasks created in Cars Fulfillment table
✔ Email notifications triggered
✔ Approved & Rejected scenarios handled
⚠ Known Issues
Payment gateway not integrated
No real-time tracking dashboard
Basic notification template
🔮 Future Enhancements
Payment Integration
Dashboard reporting
Mobile-friendly portal
SMS Notifications
Advanced workflow with SLA tracking
Inventory stock management
🎓 Learning Outcomes
ServiceNow Service Catalog Implementation
Workflow Automation
Role & Group Management
Custom Table Creation
Email Template Customization
Service Portal Integration
🙏 Acknowledgements
Developed as an academic project to demonstrate practical implementation of ServiceNow ITSM features in real-world business scenarios.
