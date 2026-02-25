# Medical Office Web Application

A full-stack web application for managing a medical practice, built with the MEAN stack. The system supports multiple user roles - patients, doctors, and staff — each with a tailored interface and access-controlled features.

## Features

- **User management** — registration, login, and role-based access control for patients, doctors, and administrative staff
- **Appointment scheduling** — patients can request, view, and track appointments; staff can approve and schedule them
- **Medical records** — doctors can create and manage exam reports per patient visit
- **Notifications** — in-app notification system for appointment updates and announcements
- **Specializations** — doctor profiles linked to medical specializations for filtering and routing appointments

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Angular, TypeScript |
| Backend | Node.js, Express.js |
| Database | MongoDB |

## Project Structure

```
├── frontend/   # Angular application
├── backend/    # Node.js + Express REST API
└── baza*.json  # MongoDB seed data (users, appointments, reports, notifications...)
```

## Getting Started

**Prerequisites:** Node.js, Angular CLI, MongoDB

```bash
# Install backend dependencies
cd backend && npm install

# Install frontend dependencies
cd frontend && npm install

# Seed the database (import JSON files into MongoDB)
mongoimport --db medicalOffice --collection korisnici --file bazaZaPredaju.korisnici.json
# Repeat for other collections...

# Start backend
cd backend && node app.js

# Start frontend
cd frontend && ng serve
```

The app will be available at `http://localhost:4200`.

## Tech Stack

`Angular` `TypeScript` `Node.js` `Express.js` `MongoDB`
