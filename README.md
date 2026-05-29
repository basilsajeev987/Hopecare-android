# Hope Care – Healthcare Staffing Management System

## Overview

**Hope Care** is a premium Android application specifically designed for healthcare staffing agencies to efficiently manage healthcare workers, care homes, staff availability, shift scheduling, and workforce operations from a centralized platform.

The system enables agency administrators to assign shifts, manage healthcare workers, monitor workforce availability, and oversee care home staffing requirements in real time. Healthcare workers can update their availability, view assigned shifts, accept schedules, and manage their work commitments directly from the mobile application.

Hope Care digitizes traditional staffing workflows, reducing administrative overhead while improving operational efficiency, workforce visibility, and communication between agencies and healthcare professionals.

---

## Features

### Administrator Features

#### Dashboard

* Premium analytics dashboard
* Real-time workforce statistics
* Worker overview
* Shift overview
* Care home management insights
* Workforce performance monitoring

#### Shift Management

* Assign shifts to workers
* Create Early, Long Day, Night, and Custom shifts
* Calendar-based scheduling
* Monitor assigned and accepted shifts
* Workforce planning tools

#### Worker Management

* View all registered healthcare workers
* Manage worker profiles
* Track worker availability
* Monitor workforce allocation

#### Care Home Management

* Add and manage care homes
* Store care home information
* Assign staff to care homes
* Maintain care facility records

#### Availability Monitoring

* View submitted worker availability
* Monitor workforce capacity
* Plan staffing requirements
* Match available workers with shifts

#### Analytics

* Worker statistics
* Shift statistics
* Acceptance rate tracking
* Workforce utilization insights
* Operational performance monitoring

---

### Healthcare Worker Features

#### Availability Management

* Submit availability from the current day until the end of the month
* Select Early, Long Day, and Night shift preferences
* Mark unavailable days
* Monthly availability planning

#### Schedule Management

* View assigned shifts
* Accept assigned shifts
* Calendar-based schedule view
* Shift history tracking

#### My Shifts

* View upcoming shifts
* View care home assignments
* Track shift status
* Access shift details

#### Profile Management

* View personal information
* Access account details
* Manage profile information

---

## Premium User Experience

Hope Care provides a modern healthcare-focused user experience with:

* Premium gradient user interface
* Professional healthcare branding
* Responsive mobile layouts
* Interactive dashboards
* Modern card-based design
* Smooth navigation
* Real-time updates
* Optimized Android performance

---

## Technology Stack

### Mobile Application (Frontend)

The Android application is built using modern React Native technologies.

* React Native
* Expo
* Expo Router
* JavaScript (ES6+)
* Axios
* AsyncStorage
* React Native Calendars
* React Native Chart Kit
* Expo Linear Gradient
* Expo Vector Icons

---

### Backend

The backend provides secure REST APIs for mobile application communication.

* Node.js
* Express.js
* JWT Authentication
* REST API Architecture
* Mongoose ODM

---

### Database

Cloud-hosted NoSQL database for scalable healthcare staffing operations.

* MongoDB Atlas

---

### Cloud Infrastructure & Deployment

#### Backend Hosting

* Render Cloud Platform

#### Database Hosting

* MongoDB Atlas Cloud Database

#### Mobile Application Build & Distribution

* Expo EAS Build
* Android APK Distribution

---

### Development Tools

* Visual Studio Code
* Git
* GitHub
* npm
* Postman

---

## System Architecture

```text
Android Application (React Native + Expo)
                │
                ▼
      REST API (Node.js + Express)
                │
                ▼
       MongoDB Atlas Database
                │
                ▼
      Hosted on Render Cloud Platform
```

---

## Authentication & Security

Hope Care implements secure authentication and authorization mechanisms.

### Security Features

* JWT Authentication
* Protected API Routes
* Role-Based Access Control
* Secure Password Storage
* Token-Based Session Management
* Secure Cloud Infrastructure

---

## User Roles

### Administrator

Responsible for:

* Managing workers
* Managing care homes
* Assigning shifts
* Monitoring analytics
* Workforce planning
* Availability management

### Healthcare Worker

Responsible for:

* Updating availability
* Viewing assigned shifts
* Accepting shifts
* Managing work schedules
* Accessing profile information

---

## Benefits for Healthcare Agencies

* Reduces manual scheduling effort
* Improves workforce planning
* Increases staffing visibility
* Enhances operational efficiency
* Simplifies shift assignment workflows
* Improves communication between staff and management
* Provides real-time workforce insights
* Supports scalable healthcare operations

---

## Installation

### Prerequisites

* Node.js
* npm
* MongoDB Atlas Account
* Render Account
* Expo CLI

---

## Frontend Setup

Install dependencies:

```bash
npm install
```

Start the application:

```bash
npx expo start
```

Run on Android:

```bash
npx expo start --android
```

---

## Backend Setup

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Run production server:

```bash
npm start
```

---

## Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret
```

---

## Build Android APK

### Configure EAS

```bash
eas build:configure
```

### Generate APK

```bash
eas build -p android --profile preview
```

### Generate Play Store Bundle

```bash
eas build -p android --profile production
```

---

## Project Structure

```text
Hope Care
│
├── frontend
│   ├── app
│   ├── assets
│   ├── services
│   ├── components
│   ├── navigation
│   └── screens
│
├── backend
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── config
│   └── server.js
│
└── README.md
```

---

## Future Enhancements

* Push Notifications
* Attendance Tracking
* Payroll Integration
* In-App Messaging
* Timesheet Management
* Shift Swapping
* Document Management
* Advanced Analytics
* Multi-Agency Support
* AI-Based Workforce Planning
* Reporting & Export Features

---

## Project Purpose

Hope Care was developed to modernize healthcare staffing operations by providing healthcare agencies with a secure, scalable, and easy-to-use workforce management solution. The application helps agencies efficiently coordinate healthcare professionals, manage care home staffing requirements, monitor workforce availability, and streamline shift scheduling through a professional Android platform.

---

## Complete Stack Summary

| Layer              | Technology                         |
| ------------------ | ---------------------------------- |
| Mobile Frontend    | React Native, Expo                 |
| Navigation         | Expo Router                        |
| UI Components      | React Native, Expo Linear Gradient |
| Charts & Analytics | React Native Chart Kit             |
| Authentication     | JWT                                |
| API Communication  | Axios                              |
| Local Storage      | AsyncStorage                       |
| Backend            | Node.js, Express.js                |
| Database           | MongoDB Atlas                      |
| ODM                | Mongoose                           |
| Cloud Hosting      | Render                             |
| Version Control    | Git & GitHub                       |
| Build System       | Expo EAS Build                     |

---

## Platform Information

**Application Name:** Hope Care
**Platform:** Android Application
**Industry:** Healthcare Staffing & Workforce Management
**Frontend:** React Native + Expo
**Backend:** Node.js + Express.js
**Database:** MongoDB Atlas
**Hosting:** Render Cloud Platform
**Build System:** Expo EAS Build
**Architecture:** Mobile App + REST API + Cloud Database

---

### Developed for Healthcare Staffing Agencies

Hope Care is designed to help healthcare agencies efficiently manage healthcare professionals, care homes, workforce availability, and shift scheduling through a modern, cloud-based Android application.
