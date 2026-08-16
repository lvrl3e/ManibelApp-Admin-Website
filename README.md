# 🚍 ManibelApp — Admin Website

> Web-based administration and transportation monitoring dashboard for the ManibelApp transportation management system.

ManibelApp Admin Website is a responsive web application designed to help administrators manage commuters, drivers, transportation operations, verification requests, incidents, reports, and monitoring data through a centralized dashboard.

The application is built with **React, TypeScript, Vite, Tailwind CSS, and REST API integration**.

---

## ✨ Features

### 🔐 Authentication & Administration

- Admin login
- Forgot password flow
- Protected routes
- Admin session management
- Remember me functionality
- Admin role support
- Account status handling
- Admin profile management
- Secure logout

### 📊 Dashboard

- Administrative overview
- Transportation-related statistics
- Summary information
- Quick access to management modules

### 👥 Commuter Management

- View commuters
- Search and manage commuter records
- View individual commuter details
- Commuter information management

### 🚗 Driver Management

- View registered drivers
- Manage driver information
- Driver-related administration

### 🪪 ID Verification

- Review commuter verification requests
- View submitted identification information
- Manage verification status

### 🚌 Jeepney Monitoring

- Monitor jeepney operations
- View jeepney information
- Live jeepney map
- Trip history
- Transportation monitoring

### 📍 Live Maps

- Jeepney live location monitoring
- Passenger live monitoring
- Interactive maps using Leaflet

### 👤 Passenger Monitoring

- Passenger monitoring dashboard
- Passenger live map
- Transportation activity monitoring

### 🚨 Incident Reports

- View reported incidents
- Review incident information
- Manage transportation-related reports

### 📈 Reports

- View administrative reports
- Generate and manage transportation data
- Export and reporting functionality

### ⚙️ Settings

- Administrative settings
- Profile management
- Application configuration

---

## 🛠️ Tech Stack

### Frontend

- React
- TypeScript
- Vite
- React Router
- Tailwind CSS
- HTML5
- CSS3

### Backend Integration

- REST APIs
- Node.js backend integration
- Authentication APIs

### Database & Data

- PostgreSQL
- Prisma
- REST API data management

### Maps & Location

- Leaflet
- React Leaflet

### Other Technologies & Tools

- QR Code generation
- ExcelJS
- Git
- GitHub
- Docker

---

### 👩‍💻 My Role

I designed and developed the ManibelApp Admin Website, including the application's frontend architecture, user interface, navigation, authentication, API integration, and administrative workflows.

My responsibilities included:
- Designing and developing the admin interface
- React frontend development
- TypeScript implementation
- Component-based architecture
- Responsive UI development
- Admin dashboard development
- Authentication implementation
- Protected route implementation
- Session management
- Login and logout functionality
- Forgot password flow
- Commuter detail pages
- Driver management
- ID verification
- Jeepney monitoring
- Jeepney live maps
- Trip history
- Passenger monitoring
- Passenger live maps
- Incident reports
- Reports
- Admin settings
- REST API integration
- API client implementation
- Interactive map functionality
- Data management
- Report and export functionality

I also implemented the application's routing and authentication architecture using React Router and a centralized authentication provider.

## 📁 Project Structure

```text
ManibelApp-Admin-Website/
│
├── public/
│
├── src/
│   ├── assets/
│   │
│   ├── components/
│   │
│   ├── lib/
│   │   ├── apiClient
│   │   └── auth
│   │
│   ├── pages/
│   │   ├── DashboardPage
│   │   ├── DriversPage
│   │   ├── CommutersPage
│   │   ├── CommuterDetailPage
│   │   ├── IdVerificationPage
│   │   ├── JeepneyMonitoringPage
│   │   ├── JeepneyLiveMapPage
│   │   ├── TripHistoryPage
│   │   ├── PassengerMonitoringPage
│   │   ├── PassengerLiveMapPage
│   │   ├── IncidentReportsPage
│   │   ├── ReportsPage
│   │   ├── SettingsPage
│   │   ├── LoginPage
│   │   └── ForgotPasswordPage
│   │
│   ├── App.tsx
│   └── main.tsx
│
├── package.json
├── vite.config.ts
├── tsconfig.json
└── README.md
