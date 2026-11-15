
# 🚀 Complaint Token Management System

### A Full-Stack Web Application for Smart Complaint Management, Automated Token Allocation & Resolution Tracking

<p align="center">
  <strong>Making complaint management more organized, transparent, and efficient through technology.</strong>
</p>

---

## 📌 Project Overview

The **Complaint Token Management System** is a full-stack web application developed to streamline complaint registration, token allocation, complaint tracking, and resolution management.

Traditional complaint-handling processes can involve manual token distribution, inefficient queue management, and limited visibility into complaint resolution progress.

This project addresses these challenges through an automated **Round Robin Token Allocation mechanism**, centralized complaint management, SLA monitoring, and an administrative dashboard.

The application combines frontend development, backend engineering, database integration, and scheduling logic to provide a structured approach to complaint management.

## ✨ Key Features

- 🎫 **Automated Token Allocation:** Implements Round Robin scheduling logic for systematic token distribution.
- 📝 **Complaint Registration:** Provides a structured interface for submitting complaints.
- 📊 **Complaint Tracking:** Supports monitoring complaint status and progress.
- ⏱️ **SLA Monitoring:** Helps track complaint resolution timelines.
- 🖥️ **Administrative Dashboard:** Provides a centralized interface for complaint management.
- 🗄️ **Database Integration:** Uses Supabase and PostgreSQL for storing and managing application data.
- 🔄 **Workflow Management:** Organizes complaint handling and token allocation processes.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | HTML5, CSS3, JavaScript, React.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | Supabase, PostgreSQL |
| Core Algorithm | Round Robin Scheduling |
| API Development | REST APIs |
| Version Control | Git, GitHub |

## 🏗️ System Architecture

The application follows a frontend-backend-database architecture.

```text
             USER / ADMIN
                  |
                  ▼
          FRONTEND INTERFACE
       HTML | CSS | JavaScript
                  |
                  ▼
              REACT.JS
                  |
                  ▼
          NODE.JS + EXPRESS
                  |
          ┌───────┴────────┐
          ▼                ▼
   TOKEN ALLOCATION   COMPLAINT
    ROUND ROBIN       MANAGEMENT
          |                |
          └───────┬────────┘
                  |
                  ▼
          SUPABASE / POSTGRESQL
                  |
                  ▼
        DASHBOARD & TRACKING
```

## ⚙️ Application Workflow

**1. Complaint Registration**

Users submit complaints through the application interface.

**2. Automated Token Generation**

The system uses Round Robin scheduling logic to allocate tokens systematically.

**3. Database Management**

Complaint information and related records are managed through the configured Supabase and PostgreSQL integration.

**4. Complaint Monitoring**

Administrators can use the management interface to monitor complaints and their progress.

**5. SLA Tracking**

The application supports monitoring complaint resolution timelines and operational status.

## 💻 Installation & Local Setup

### Prerequisites

- Node.js
- npm
- Git
- Supabase account and project

### Step 1: Clone the Repository

```bash
git clone https://github.com/Bhoomika-git11/complaint-token-system.git
cd complaint-token-system
```

### Step 2: Install Dependencies

Navigate to the frontend and backend directories and install their dependencies.

```bash
npm install
```

Repeat this step in each directory containing a `package.json` file.

### Step 3: Configure Environment Variables

Configure the environment variables required by your application, including Supabase connection details.

Never commit passwords, private keys, or sensitive credentials to GitHub.

### Step 4: Run the Application

Start the frontend and backend using the development scripts specified in their respective `package.json` files.

**Note:** The application has been developed and tested locally. A public live deployment is not currently available.

## 🎯 Technical Skills Demonstrated

- Full-Stack Web Development
- Frontend Development
- Backend Development
- REST API Integration
- Database Management
- Round Robin Scheduling Algorithm
- Application Workflow Design
- Problem Solving
- Git and GitHub

## 🔮 Future Enhancements

- Public cloud deployment
- Real-time complaint status notifications
- Advanced analytics and reporting
- Enhanced role-based access control
- Intelligent complaint prioritization
- Improved dashboard visualizations

## 👩‍💻 Author

### Bhoomika Takkar

BSc Research in AI and Data Science

- **GitHub:** [Bhoomika-git11](https://github.com/Bhoomika-git11)
- **LinkedIn:** [Bhoomika Takkar](https://linkedin.com/in/bhoomika11)

---

<p align="center">
  <strong>Built with the goal of improving complaint management through technology and automation.</strong>
</p>
