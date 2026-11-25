# 🎓 Smart Campus Placement Management System

A full-stack campus recruitment platform designed to simplify and organize placement activities by connecting students, recruiters, and placement officers through a centralized application.

## 📌 Project Overview

The Smart Campus Placement Management System aims to modernize the college placement process by providing a centralized platform for managing student profiles, recruitment opportunities, job applications, and placement activities.

The application follows a microservices-oriented backend structure with a separate frontend application.

## 🚀 Key Modules

The repository contains the following backend services:

- **API Gateway:** Entry point for routing application requests.
- **Authentication Service:** Handles user authentication.
- **User Service:** Manages user-related information.
- **Job Service:** Handles job-related operations.
- **Feed Service:** Manages feed-related functionality.
- **Notification Service:** Supports notification functionality.

### Frontend
- React-based frontend application.
- Component-based UI structure.
- Vite development and build tooling.
- API integration utilities.

## 🛠️ Technology Stack

| Category | Technology |
|---|---|
| Backend | Java, Spring Boot |
| Frontend | React.js |
| Build Tool | Maven |
| Frontend Tool | Vite |
| Database | Verify configured database |
| Architecture | Microservices |
| Containerization | Docker, Docker Compose |
| Version Control | Git, GitHub |

## 🏗️ Project Structure

```text
smart-campus-placement-system/
│
├── decp-backend/
│   ├── api-gateway/
│   ├── auth-service/
│   ├── feed-service/
│   ├── job-service/
│   ├── notification-service/
│   └── user-service/
│
├── decp-frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── docker-compose.yml
├── .gitignore
└── README.md
```

## 💡 Project Goals

- Simplify campus recruitment activities.
- Organize student and recruiter information.
- Provide a centralized recruitment platform.
- Improve placement-related information management.
- Demonstrate practical implementation of microservices and full-stack development.

## ⚙️ Development Environment

The project can be developed using:

- Java Development Kit (JDK)
- Node.js and npm
- Maven
- MySQL or the database configured by the project
- Visual Studio Code or IntelliJ IDEA
- Docker Desktop
- Git

## ▶️ Getting Started

1. Clone the repository:

```bash
git clone https://github.com/harshpreet91/smart-campus-placement-system-2026.git
```

2. Navigate to the project directory:

```bash
cd smart-campus-placement-system-2026
```

3. Configure the required environment variables locally.

4. Install frontend dependencies:

```bash
cd decp-frontend
npm install
```

5. Review the backend Maven configurations and Docker Compose configuration before starting the services.

Refer to the individual service configurations for the exact startup commands and database requirements.

## 🔐 Security

- Environment-specific configuration should be maintained locally.
- Never commit passwords, API keys, tokens, or private credentials.
- Use the provided `.gitignore` rules to protect sensitive files.

## 🔮 Future Enhancements

- AI-based resume analysis.
- Intelligent job recommendations.
- Automated eligibility verification.
- Interview scheduling.
- Advanced placement analytics.
- Email and real-time notifications.

## 👨‍💻 Developer

**GitHub:** [harshpreet91](https://github.com/harshpreet91)

## 📂 Repository

[Smart Campus Placement Management System](https://github.com/harshpreet91/smart-campus-placement-system-2026)

---

*Academic and portfolio project focused on full-stack development and microservices architecture.*