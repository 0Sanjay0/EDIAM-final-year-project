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

  ## Screenshots

### Home / Landing Page
![EDIAM Home Page](<img src="https://github.com/user-attachments/assets/6a73979d-5235-4a7c-8258-3ac27f910c0a" alt="EDIAM Home Page" width="800">
)

### Emergency Access
![EDIAM Emergency Access](<img src="https://github.com/user-attachments/assets/1eba3ccf-6014-42f9-a0fc-9a0c293356ab" alt="EDIAM Emergency Page" width="800">
)

### Patient Dashboard
![EDIAM Patient Dashboard](<img src="https://github.com/user-attachments/assets/90276374-d36b-4541-aade-ccc721951ad2" alt="EDIAM Patient Dashboard Page" width="800">
)

### Admin Dashboard
![EDIAM Admin Dashboard](<img src="https://github.com/user-attachments/assets/cb87423d-1847-4754-93f6-66a7f3839da2" alt="EDIAM Admin Dashboard Page" width="800">
)

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
```

## API

The backend provides 30+ REST APIs covering core healthcare workflows, including:

- Authentication and authorization
- Patient management
- Doctor and hospital operations
- Appointments
- Prescriptions
- Laboratory reports
- Emergency access
- Administrative operations

The APIs are consumed by the React frontend through the Express.js backend.

## Security

The application implements several mechanisms to protect healthcare data and control access:

- JWT-based authentication
- Role-Based Access Control (RBAC)
- Protected API routes
- Role-specific access to healthcare information
- QR-based emergency access
- Emergency access logging and audit tracking
- Environment variables for sensitive configuration

## Getting Started

### Prerequisites

Make sure the following are installed:

- Node.js
- npm
- MongoDB Atlas account

### Clone the Repository

```bash
git clone YOUR_REPOSITORY_URL
cd EDIAM-final-year-project
```

### Backend Setup

```bash
cd healthcare-backend
npm install
npm run dev
```

### Frontend Setup

Open a new terminal:

```bash
cd healthcare-frontend
npm install
npm run dev
```

## Environment Variables

The frontend and backend directories each contain an `.env.example` file.

Before running the application locally:

1. Create a `.env` file in `healthcare-frontend`.
2. Create a `.env` file in `healthcare-backend`.
3. Copy the required variable names from the corresponding `.env.example` files.
4. Add your local configuration values.

> Never commit `.env` files, database credentials, JWT secrets, API keys, or other sensitive information to the repository.

## Live Demo

[View Live Application](https://ediam-healthcare.vercel.app/)

## Project Status

Completed
