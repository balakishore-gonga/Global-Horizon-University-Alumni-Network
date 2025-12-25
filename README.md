# Global-Horizon-University-Alumni-Network
A production-ready, cloud-native full-stack alumni engagement platform Built with modern React, FastAPI, MongoDB, and Docker — designed using real SaaS architecture standards.
Project Overview

🚀 The Global Horizon University Alumni Network is a full-stack web application that provides a centralized digital ecosystem for alumni engagement.
It enables event participation, donations, alumni networking, feedback, and secure communication — all through a scalable, containerized, cloud-ready architecture.

This project is built using enterprise engineering practices and mirrors how modern SaaS platforms are designed in real organizations.

🧱 System Architecture
[ React Frontend ]  →  [ FastAPI Backend ]  →  [ MongoDB Database ]
        │                      │                      │
        └──────── Docker & Docker Compose Orchestration ────────┘

Layer	Technology
Frontend	React 19, Tailwind CSS, Shadcn UI
Backend	FastAPI (Async Python)
Database	MongoDB
API Style	RESTful
Authentication	JWT
DevOps	Docker, Docker Compose
Validation	Zod (Frontend), Pydantic (Backend)
✨ Key Features

• Secure user registration & login
• Alumni profiles & networking
• Event listing and registrations
• Real-time in-app messaging
• Donation management
• Feedback submission
• Admin dashboard statistics
• Fully responsive & accessible UI

🖥️ Tech Stack
Frontend

React 19

Tailwind CSS

Shadcn/UI + Radix UI

Axios

React Hook Form + Zod

Sonner (notifications)

Backend

FastAPI

Motor (Async MongoDB)

Pydantic

JWT Authentication

Bcrypt password hashing

Database

MongoDB

DevOps

Docker

Docker Compose

📁 Project Structure
/app
├── backend/
│   ├── server.py
│   ├── requirements.txt
│   ├── .env
│   └── Dockerfile
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── App.js
│   │   └── App.css
│   ├── public/
│   ├── package.json
│   └── Dockerfile
└── docker-compose.yml

🔐 Security & Best Practices

JWT-based authentication

Password hashing using bcrypt

Input validation (Zod + Pydantic)

Protected routes

Environment-based CORS configuration

Modular architecture

Dockerized deployment

⚡ Performance Optimizations

Lazy loading React components

Async API operations

MongoDB optimized queries

Code splitting and asset optimization

🐳 Run Locally
Prerequisites

Docker

Docker Compose

Start the Application
docker-compose up --build


Frontend will run on: http://localhost:3000
Backend API will run on: http://localhost:8000

📈 Future Enhancements

OAuth login (Google / LinkedIn)

Payment gateway (Stripe / PayPal)

Real-time chat with WebSockets

Email notifications

Analytics dashboard

CI/CD pipeline

PWA support

🎯 Why This Project Stands Out

✔ Designed using real SaaS architecture patterns
✔ Cloud-native and production-ready
✔ Fully containerized
✔ Clean modular codebase
✔ Enterprise-grade security practices
✔ Demonstrates full-stack, DevOps, and system design proficiency

👨‍💻 Author

Bala Kishore Gonga
Full Stack & Data Engineer
React | FastAPI | MongoDB | Docker | Cloud | BI | Data Engineering
