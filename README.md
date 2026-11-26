# FixMyCity – Geo-Based Smart Civic Complaint Management System

## Project Overview

FixMyCity is a web-based civic complaint management system designed to help citizens report local infrastructure and public service issues and track their resolution.

The platform connects citizens, municipal officers, department staff, and administrators through a centralized complaint management interface.

The main objective is to improve communication between citizens and municipal authorities and make complaint resolution more transparent and efficient.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- LocalStorage (if implemented)
- JSON (Mock Data, if implemented)

## User Roles

1. **Citizen:** Register complaints, upload photographs, view submitted complaints, and track complaint status.
2. **Municipal Officer:** Review complaints, assign them to department staff, and manage complaint assignments.
3. **Department Staff:** View assigned complaints, add inspection notes, update complaint status, and submit resolution details.
4. **Administrator:** Monitor users and complaints, manage departments, and view system statistics.

## Key Features

- User registration and login.
- Role-based dashboards for different users.
- Civic complaint submission with category and description.
- Complaint location details and photograph upload.
- Unique complaint reference numbers.
- Complaint assignment to departments and staff.
- Complaint status tracking and history timeline.
- Inspection notes and resolution details.
- Complaint and completion photograph previews.
- Department management.
- Dashboard statistics and complaint monitoring.
- Responsive user interface.

## Project Structure

```text
FIX-MY-CITY/
│
├── css/
│   └── style.css
│
├── js/
│   ├── auth.js
│   ├── complaints.js
│   ├── dashboard.js
│   ├── my-complaints.js
│   ├── track.js
│   ├── officer-dashboard.js
│   ├── staff-dashboard.js
│   └── admin-dashboard.js
│
├── pages/
│   ├── register.html
│   ├── login.html
│   ├── citizen-dashboard.html
│   ├── add-complaint.html
│   ├── my-complaints.html
│   ├── track-complaint.html
│   ├── officer-dashboard.html
│   ├── staff-dashboard.html
│   └── admin-dashboard.html
│
├── index.html
└── README.md
```

*Note: Update this folder structure to match your actual GitHub files.*

## How to Run the Project

1. Clone or download this repository.
2. Extract the downloaded project folder.
3. Open the project folder in Visual Studio Code.
4. Install the Live Server extension.
5. Open `index.html`.
6. Right-click and select **Open with Live Server**.
7. Register an account and explore the available dashboards.

## Current Implementation

FixMyCity is designed as a web-based civic complaint management platform with separate interfaces for citizens, municipal officers, department staff, and administrators.

The frontend provides the user interface and complaint management workflows.

The actual storage, authentication, and backend implementation depend on the connected application code.

## Future Enhancements

- Backend API integration.
- Secure authentication and role-based authorization.
- Database integration for persistent storage.
- Server-side image upload and storage.
- Map integration for geographic complaint visualization.
- Email and SMS notifications.
- Deployment to a production hosting environment.

## Project Status

The project focuses on developing a centralized civic complaint management platform. Further development can include backend integration, database connectivity, security improvements, and deployment.

---

**Project Name:** FixMyCity  
**Project Type:** Web-Based Application  
**Domain:** Smart City / Civic Complaint Management System
