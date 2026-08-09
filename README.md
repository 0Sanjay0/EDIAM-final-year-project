# EDIAM – Healthcare Management Platform

## Overview

EDIAM is a full-stack healthcare management platform designed to connect patients, doctors, hospitals, laboratories, and administrators through a centralized system.

The platform provides role-based access to healthcare data and includes QR-based emergency access, appointment management, prescriptions, laboratory reports, and administrative workflows.

## Key Features

- Role-based access for Patients, Doctors, Hospitals, Laboratories, and Administrators
- JWT-based authentication and authorization
- QR-based emergency access to patient information
- Appointment management
- Prescription management
- Laboratory report management
- Administrative approval and management workflows
- Emergency access logging and audit tracking
- REST API-based frontend and backend communication
- Responsive user interface

## Technology Stack

### Frontend
- React.js
- Tailwind CSS

### Backend
- Node.js
- Express.js
- REST APIs
- JWT Authentication

### Database
- MongoDB Atlas
- Mongoose

### Deployment
- Vercel
- Render

## Project Structure

```text
EDIAM-final-year-project/
├── healthcare-frontend/
└── healthcare-backend/

## API

The application contains 30+ REST APIs covering authentication, patient management, appointments, prescriptions, laboratory reports, emergency access, and administrative operations.

## Security
- JWT authentication
- Role-Based Access Control (RBAC)
- Protected API routes
- Emergency access logging
- Environment-based configuration

## Live Demo

https://ediam-healthcare.vercel.app/

## Getting Started
### Prerequisites
- Node.js
- pnpm
- MongoDB Atlas account
### Clone the repository
git clone YOUR_REPOSITORY_URL
cd EDIAM-final-year-project
#### Frontend
cd healthcare-frontend
pnpm install
pnpm dev
#### Backend
cd healthcare-backend
pnpm install
pnpm dev

##Environment Variables
Environment variable examples are provided separately in the frontend and backend directories.
Create the required .env files using the provided .env.example files before running the application.

## Project Status
Completed

## Future Improvements
- Enhanced administrative analytics
- Additional healthcare workflows
- Further security and performance improvements
