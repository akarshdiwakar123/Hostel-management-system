# College Hostel Counselling System (CHCS)

🚀 **Live Deployment:** [View the platform on Vercel here](https://hostel-management-system-sooty.vercel.app/)

A modern, enterprise-grade static web application designed to streamline hostel management and administrative tasks for educational institutions. The platform provides entirely separate dedicated interfaces for Students and Administrators (Employees), connected through a centralized, responsive dashboard system.

---

## 🌟 Key Features

### 🎓 Student Portal
A digital hub for residents to access hostel services and manage their accommodation asynchronously.
*   **Secure Authentication:** Isolated student login system with session persistence.
*   **Dashboard Overview:** Instant insights into room status, fee deficities, pending leaves, and active complaints.
*   **Profile & Room Tracking:** Detailed view of student information, allocated room facilities, and roommate mapping.
*   **Mess Menu Integrations:** Interactive week-by-week dynamic mess menu filtering (Vegetarian/Non-Vegetarian/Egg delineations).
*   **Complaint & Leave Systems:** Built-in form submission interfaces for raising maintenance tickets and applying for out-of-campus leaves.

### 💼 Employee & Admin Portal
A comprehensive administrative toolkit for hostel wardens, managers, and administrative staff to process tasks seamlessly.
*   **Administrative Tracking:** Macro-level monitoring of hostel capacity, offline fee verifications, and urgent infrastructure alerts.
*   **Student Roster Management:** Searchable and filterable student directory for tracking occupancy and contacting residents.
*   **Actionable Complaints Inbox:** Centralized ticketing queue with dynamic "Resolve" state alterations for plumbing, electrical, and maintenance issues.
*   **Leave Authorizations:** Approvals interface for monitoring and responding to active student leave requests.
*   **Offline Fee Verifications:** Secure workspace to authenticate and document offline physical fee transitions (Cheques/Demand Drafts).

---



## 📁 Core Project Structure

```text
Hostel-management-system/
├── index.html                 # Main Landing Gateway
├── style.css                  # Global Design System Defaults & Tokens
├── student_login.html         # Student portal authentication
├── student_dashboard.html     # Student hub & metrics
├── stu_profile.html           # Student information breakdown
├── stu_room.html              # Room & roommate mapping
├── stud_fees.html             # Institutional fee breakdowns
├── stu_mess.html              # Diet planning & mess filtering
├── stu_leave.html             # Absence requisition tracking
├── stu_complaint.html         # Live maintenance reporting
├── employee_login.html        # Employee/Admin secure login
├── employee_dashboard.html    # Global administrative view
├── emp_students.html          # Hostel roster / Search mechanism
├── emp_complaints.html        # Complaint queue and resolution engine
├── emp_leave.html             # Central absence approval system
└── emp_fees.html              # Offline verification ledger
```

---
*Developed for robust, hassle-free administrative efficiency.*
