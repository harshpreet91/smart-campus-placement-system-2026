# Smart Campus Placement Management System 🎓

A full-stack campus placement management platform built to streamline recruitment activities and connect students, recruiters, and placement officers through a centralized application.

## 📌 About the Project

The Smart Campus Placement Management System is designed to simplify and organize the college recruitment process.

The application uses a microservices-oriented backend architecture with a React frontend. It provides separate backend services for authentication, user management, jobs, feeds, notifications, and API routing.

The project aims to provide a scalable foundation for managing campus placement activities.

## ✨ Backend Services

| Service | Responsibility | Port |
|---|---|---:|
| API Gateway | Central request routing | 8080 |
| Auth Service | Authentication | 8081 |
| User Service | User management | 8082 |
| Feed Service | Feed operations | 8083 |
| Job Service | Job operations | 8084 |
| Notification Service | Notifications | 8085 |

## 🛠️ Technology Stack

### Frontend
- React 19
- Vite 8
- React Router 7
- Axios
- TanStack Query
- Zustand
- React Hook Form
- Zod
- JWT Decode
- Lucide React

### Backend
- Java 17
- Spring Boot 4.0.5
- Spring Data JPA
- Spring WebMVC
- Spring Validation
- JWT (JJWT)
- Lombok
- Maven

### Database and Infrastructure
- PostgreSQL 16
- Apache Kafka 7.5
- Apache Zookeeper
- Docker
- Docker Compose

## 🏗️ Project Architecture

```text
                    React Frontend
                      Port 5173
                          |
                          v
                      API Gateway
                      Port 8080
                          |
       +------------------+------------------+
       |         |        |        |         |
       v         v        v        v         v
      Auth      User     Feed     Job    Notification
     Service   Service  Service Service   Service
       |         |        |        |         |
       v         v        v        v         v
    PostgreSQL PostgreSQL PostgreSQL PostgreSQL PostgreSQL
       |                  |        |
       +------------------+--------+
                          |
                    Apache Kafka
                          |
                      Zookeeper
```

## 📁 Project Structure

```text
smart-campus-placement-system/
│
├── decp-backend/
│   ├── api-gateway/
│   ├── auth-service/
│   ├── user-service/
│   ├── feed-service/
│   ├── job-service/
│   └── notification-service/
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

## ⚙️ Prerequisites

Install the following tools:

- Java Development Kit (JDK) 17
- Node.js and npm
- Docker Desktop
- Git
- Maven (or use the Maven wrapper if provided)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/harshpreet91/smart-campus-placement-system-2026.git
cd smart-campus-placement-system-2026
```

### 2. Configure environment variables

The application expects environment files for its services.

Create and configure the required local environment files:

- decp-backend/api-gateway/.env
- decp-backend/auth-service/.env
- decp-backend/user-service/.env
- decp-backend/feed-service/.env
- decp-backend/job-service/.env
- decp-backend/notification-service/.env
- decp-frontend/.env

Use the required variable names from the respective service configurations. Never commit real credentials or secret keys.

### 3. Start infrastructure and backend services

From the root directory:

```bash
docker compose up --build
```

This Compose configuration starts PostgreSQL databases, Kafka, Zookeeper, backend services and the frontend.

### 4. Frontend development

For local frontend development:

```bash
cd decp-frontend
npm install
npm run dev
```

### 5. Build frontend

```bash
npm run build
```

## 🔐 Security

- JWT-based authentication dependencies are included.
- Environment-specific configuration is maintained outside source control.
- Credentials and API secrets should never be committed to GitHub.

## 🔮 Future Enhancements

- AI-based resume analysis.
- Intelligent job recommendations.
- Automated student eligibility verification.
- Interview scheduling.
- Advanced placement analytics.
- Real-time notifications.

## 🎯 Project Objectives

- Centralize campus placement activities.
- Organize student and recruiter information.
- Simplify job application management.
- Demonstrate microservices architecture.
- Apply full-stack development concepts.
- Explore event-driven communication using Kafka.

## 👨‍💻 Developer

**GitHub:** [harshpreet91](https://github.com/harshpreet91)

## 📂 Repository

[Smart Campus Placement Management System](https://github.com/harshpreet91/smart-campus-placement-system-2026)

---

*Academic and portfolio project focused on full-stack development, backend engineering and microservices architecture.*