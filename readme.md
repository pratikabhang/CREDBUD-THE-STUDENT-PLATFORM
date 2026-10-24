# 🎓 CREDBUD — The Student Platform

> Empowering students and educators with smart attendance tracking, role-based dashboards, academic analytics, and centralized student management.

![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?logo=nodedotjs&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Integration-FFCA28?logo=firebase&logoColor=black)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-blue)
![Status](https://img.shields.io/badge/Status-Active%20Development-brightgreen)

## 🌟 Live Deployments

| Component | Link |
|---|---|
| 🚀 Main Application | [credbudapp.netlify.app](https://credbudapp.netlify.app/) |
| 💻 Alternative Frontend | [credbudstudent.netlify.app](https://credbudstudent.netlify.app/) |
| ⚙️ Backend API | [credbudbackend.onrender.com](https://credbudbackend.onrender.com/) |
| 🌐 Project Website | [credbud-the-student-platform.vercel.app](https://credbud-the-student-platform.vercel.app/) |

## 📂 Project Repositories

CredBud is organized into separate repositories for the main platform, frontend application, and backend API.

| Component | Repository | Description |
|---|---|---|
| 🎓 Main Project | [CREDBUD-THE-STUDENT-PLATFORM](https://github.com/pratikabhang/CREDBUD-THE-STUDENT-PLATFORM) | Main project repository containing the platform's frontend and backend directories |
| 💻 Frontend | [CREDBUD-FRONTEND](https://github.com/pratikabhang/CREDBUD-FRONTEND) | React-based web interface and client-side functionality |
| ⚙️ Backend | [CREDBUD-BACKEND-API-Server](https://github.com/pratikabhang/CREDBUD-BACKEND-API-Server) | Node.js and Express REST API |

The frontend and backend repositories are maintained separately to support independent development, testing, and deployment.

## 📖 Overview

CREDBUD is a student-focused platform designed to simplify academic management and improve collaboration between students, educators, and administrators.

The platform brings together attendance tracking, student profiles, course management, academic analytics, notifications, and role-based dashboards in one digital environment.

### 🎯 Objectives

- Simplify attendance recording and monitoring.
- Improve visibility into student attendance and academic performance.
- Provide role-specific access to students, staff, and administrators.
- Centralize academic information and student engagement tools.
- Support web-based access and mobile application development.

## 🏆 Key Features

### 👥 Role-Based Access Control

- **Students:** View attendance, academic information, and achievements.
- **Staff:** Manage supported academic activities and attendance.
- **Administrators:** Access management dashboards and administrative functions.
- **Moderators:** Monitor and manage permitted platform content and data.

### 📷 Smart Attendance Management

- QR-code-based attendance workflows.
- Digital attendance records.
- Attendance monitoring and reporting.
- Optional location-based verification where implemented.

### 📊 Analytics and Reporting

- Dashboard-based attendance insights.
- Student performance monitoring.
- Attendance summaries and reports.
- Data visualization for supported metrics.

### 🧑‍🎓 Student and Staff Management

- Student profile management.
- Staff profile management.
- Academic information organization.
- Achievement and badge tracking.

### 📚 Academic Management

- Subject and course management.
- Announcements and posts.
- Academic material sharing where supported.
- Centralized access to relevant academic information.

### 🔔 Notifications and Engagement

- Notifications for important updates where configured.
- Student engagement features.
- Achievement tracking.
- Communication through supported platform features.

### 📱 Cross-Platform Experience

- Responsive web application.
- Separate frontend and backend codebases.
- Mobile application support where the corresponding mobile implementation is available.

Feature availability depends on the current implementation and deployment configuration.

## 🛠️ Technology Stack

### Frontend

- React.js
- JavaScript and TypeScript, according to the relevant frontend project
- Vite or Create React App, depending on the frontend codebase
- Tailwind CSS
- Chakra UI
- Firebase SDK
- Axios

### Backend

- Node.js
- Express.js
- REST API architecture
- Middleware-based request processing
- Firebase integration
- JWT and Firebase Authentication integrations where configured

### Database and Authentication

- Firebase Firestore
- Firebase Authentication
- JSON Web Tokens (JWT), where implemented

### Mobile Development

- Flutter
- Dart
- Android Studio

### Development and Deployment

- Git and GitHub
- Netlify for frontend hosting
- Render for backend hosting
- Vercel for the project website
- Postman for API testing
- Chrome DevTools for browser debugging

The separate frontend and backend repositories may use different dependency versions and configurations. Consult their individual README files for exact requirements.

## 🏗️ Architecture

```text
                    Students / Staff / Admins
                              |
                              v
                       Web Application
                              |
                              v
                       Frontend Layer
                              |
                         REST API
                              |
                              v
                       Backend Server
                              |
                 +------------+------------+
                 |            |            |
                 v            v            v
             User/Auth    Attendance    Academic
              Modules      Modules      Modules
                 |            |            |
                 +------------+------------+
                              |
                              v
                     Firebase Services
                 Authentication / Firestore
                              |
                              v
                   Reports and Dashboards
```

This diagram represents the platform's high-level logical architecture. Actual data flows depend on the implementation of each module.

## 📁 Repository Structure

The main repository contains the following project components:

```text
CREDBUD-THE-STUDENT-PLATFORM/
├── CREDBUD THE STUDENT PLATFORM/
├── credbud-frontend/
├── credbud-backend/
├── .gitignore
└── readme.md
```

The separately maintained repositories are:

```text
CREDBUD-FRONTEND/
├── public/
├── src/
├── package.json
└── README.md
```

```text
CREDBUD-BACKEND-API-Server/
├── controllers/
├── middleware/
├── routes/
├── utils/
├── app.js
├── package.json
└── README.md
```

Refer to each repository's current source tree for the complete file structure.

## 🚀 Getting Started

### Prerequisites

Install the tools required for the components you want to run:

- Git
- Node.js and npm
- A Firebase project with the required services configured
- Flutter SDK and Android Studio if developing the mobile application

Verify your installation:

```bash
git --version
node --version
npm --version
flutter --version
```

Use the Node.js and package versions supported by the individual frontend and backend repositories.

### 1. Clone the Main Repository

```bash
git clone https://github.com/pratikabhang/CREDBUD-THE-STUDENT-PLATFORM.git
cd CREDBUD-THE-STUDENT-PLATFORM
```

### 2. Run the Frontend

For the standalone frontend repository:

```bash
git clone https://github.com/pratikabhang/CREDBUD-FRONTEND.git
cd CREDBUD-FRONTEND
npm install
npm start
```

Follow the frontend README if the current version uses a different development command.

### 3. Run the Backend

For the standalone backend repository:

```bash
git clone https://github.com/pratikabhang/CREDBUD-BACKEND-API-Server.git
cd CREDBUD-BACKEND-API-Server
npm install
npm run dev
```

Use the backend's documented production command when deploying the API.

### 4. Configure Environment Variables

Create the required environment files according to the instructions in each repository.

Typical configuration categories include:

- Frontend API base URL.
- Firebase client configuration.
- Backend port and runtime environment.
- Authentication secrets.
- Firebase Admin credentials where required.

Variable names differ between the projects, so use their respective `.env.example` files or source-code configuration.

**Security:** Never commit real `.env` files, JWT secrets, Firebase Admin private keys, or other sensitive credentials.

### 5. Connect Frontend and Backend

1. Start the backend API.
2. Configure the frontend to use the correct API base URL.
3. Ensure the backend permits requests from the frontend origin.
4. Verify authentication and API connectivity.
5. Test the relevant platform workflows.

The live deployments and local development environments may use different API URLs.

## 📚 Research Publications and References

### 🔬 Publications

- **Survey Publication:** [CREDBUD: The Ultimate Student Platform — IJRASET](https://www.ijraset.com/research-paper/credbud-the-ultimate-student-platform)
- **Final Publication:** [CREDBUD: The Student Platform — ISJEM](https://isjem.com/download/credbud-the-student-platform/)

### 📑 Additional References

- Gawali & Suralkar: [IEEE Xplore — Document 9681472](https://ieeexplore.ieee.org/document/9681472)
- Sarkar et al.: [IEEE Xplore — Document 9134225](https://ieeexplore.ieee.org/document/9134225)
- Kaur & Kaur: [IEEE Xplore — Document 10404725](https://ieeexplore.ieee.org/document/10404725)

These references provide background on related attendance-management systems and technologies. Consult the original publications for their verified titles, author lists, and publication years.

## 🔐 Security Considerations

- Enforce role-based authorization on the backend.
- Validate QR attendance requests on the server.
- Protect student information and authentication credentials.
- Configure Firebase security rules appropriately.
- Restrict CORS to trusted frontend origins in production.
- Validate all incoming requests.
- Use HTTPS for deployed services.
- Avoid exposing sensitive student data in logs or public reports.

## 🔮 Future Improvements

Potential enhancements include:

- Expanded automated testing.
- Improved accessibility and responsive design.
- Additional analytics and reporting options.
- Stronger monitoring and error handling.
- Improved API documentation.
- More comprehensive mobile integration.
- Automated build and deployment checks.

These are proposed improvements rather than claims about features already implemented.

## 🤝 Contributing

Contributions, bug reports, and suggestions are welcome.

1. Fork the relevant repository.
2. Create a feature branch.
3. Implement and test your changes.
4. Commit your changes with a descriptive message.
5. Push your branch and open a pull request.

```bash
git checkout -b feature/your-feature-name
git add .
git commit -m "Improve student platform functionality"
git push origin feature/your-feature-name
```

For frontend-specific or backend-specific changes, use the corresponding standalone repository.

## 📄 License

Refer to the `LICENSE` file in the relevant repository for the applicable license and usage terms.

## 👨‍💻 Author

**Pratik Abhang**

- GitHub: [@pratikabhang](https://github.com/pratikabhang)
- Main Project: [CREDBUD-THE-STUDENT-PLATFORM](https://github.com/pratikabhang/CREDBUD-THE-STUDENT-PLATFORM)
- Frontend: [CREDBUD-FRONTEND](https://github.com/pratikabhang/CREDBUD-FRONTEND)
- Backend: [CREDBUD-BACKEND-API-Server](https://github.com/pratikabhang/CREDBUD-BACKEND-API-Server)

---

⭐ If you find CredBud useful, consider starring the [main repository](https://github.com/pratikabhang/CREDBUD-THE-STUDENT-PLATFORM).

*Simplifying academic management. Improving engagement. Empowering students.*
