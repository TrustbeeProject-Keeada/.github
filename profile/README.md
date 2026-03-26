# Welcome to TrustBee

TrustBee is a modern **full-stack job platform** designed to connect **job seekers** and **employers** through a clean, user-friendly, and intelligent digital experience. The platform simplifies the recruitment process by providing tools for job discovery, profile management, employer job posting, communication, and smart CV-to-job matchmaking.

The system is built with a **scalable architecture**, using a clear separation between frontend and backend. The backend leverages **Prisma ORM** with **PostgreSQL** for data management, and the project uses **Docker** to ensure consistent development and deployment environments.

<p align="left">
  <img src="../profile/trustbee.png" width="300" />
</p>
---

## Table of Contents

1. [Features](#features)  
2. [Tech Stack](#tech-stack)  
3. [Frontend Overview](#frontend-overview)  
4. [Backend Overview](#backend-overview)  
5. [Ethical and Inclusive Design](#ethical-and-inclusive-design)  
6. [Installation](#installation)  
7. [Docker Setup](#docker-setup)  
8. [Environment Variables](#environment-variables)  
9. [Database & Prisma](#database--prisma)  
10. [Folder Structure](#folder-structure)  
11. [Future Improvements](#future-improvements)  
12. [Authors](#authors)

---

## Features

TrustBee includes a comprehensive set of features for both **job seekers** and **employers**:

**Job Seeker Features:**
- Browse and filter job listings (type, education, location, keyword)  
- View detailed job descriptions  
- Save/bookmark jobs and track applied jobs  
- Update profile with experience, education, CV, and social links  
- AI Assistant for job search guidance  
- Receive CV-to-job match scores for better opportunity discovery  
- Messaging interface for communication with employers  

**Employer Features:**
- Create, edit, and manage job listings  
- Track applicants for posted jobs  
- View candidate profiles  
- Messaging interface to communicate with applicants  

**General Platform Features:**
- Landing page with platform information and feature highlights  
- Authentication flow: register, login, reset password  
- Dashboard with stats, activity feed, and quick actions  
- Dark/light mode with modern branding and UI components  
- Responsive and intuitive design  
- Fair, inclusive, and ethical job matching and recommendation system  

---

## Tech Stack

### Frontend
- React  
- TypeScript  
- Tailwind CSS  
- Context API for state management  

### Backend
- Node.js  
- Express.js  
- Prisma ORM  

### Database
- PostgreSQL  

### DevOps / Environment
- Docker & Docker Compose  
- REST API architecture  
- Authentication & Authorization  

---

## Frontend Overview

The frontend is responsible for the **user interface and experience**. It includes:

- Responsive pages for landing, authentication, dashboard, jobs, profiles, messages, saved items, AI assistant, and support.  
- **CV-to-job matchmaking** functionality implemented to match candidate profiles to relevant job listings.  
- Employer-specific tools for job creation and management.  
- Context-based state management (`AuthContext` and `JobContext`) for authentication, user sessions, and job data.  
- Modern UI with dark/light modes, dark green and gold accents, glassmorphism cards, and the TrustBee bee logo integrated throughout the app.  

---

## Backend Overview

The backend manages all **server-side logic and data operations**:

- User authentication and authorization  
- Job management (CRUD)  
- Profile management  
- Applications and saved jobs tracking  
- Messaging and AI assistant support  
- API endpoints for frontend communication  
- Prisma ORM provides type-safe database access and schema management  
- PostgreSQL stores all persistent application data  

The backend is designed to be **scalable, maintainable, and secure**, separating business logic from the frontend UI.

---

## Ethical and Inclusive Design

TrustBee is designed to support a **fair, inclusive, and professional recruitment experience**:

- Job opportunities and recommendations are based on **skills, qualifications, experience, and profile-job compatibility**.  
- The system **does not favor or discriminate** against users based on race, ethnicity, religion, gender, nationality, or other unrelated personal characteristics.  
- CV-to-job matchmaking focuses on **relevant professional criteria** to create a more objective and equal recruitment process.  
- Fairness, inclusivity, and responsible design are core principles guiding the development of TrustBee.

---
