# Zimbabwe School Management System

A comprehensive, integrated school management system tailored for Zimbabwe high schools (Forms 1-6). The system provides dedicated portals for Administrators, Teachers, and Students with both web and mobile applications.

## 📋 Project Overview

This system streamlines school operations by providing role-based access and functionality:

### **Administration Portal**
- Register, view, edit, and manage all student records
- Track school fees and payments
- Generate school reports
- Manage teacher assignments and timetables
- Handle all administrative duties

### **Teacher Portal**
- View assigned classes and student lists
- Access and manage student academic records
- Create, send, and manage assignments
- Distribute notes and tests
- Track student progress
- View class timetables and schedules

### **Student Portal**
- View personal, academic, and sporting records
- Access school work (assignments, notes, tests)
- Submit assignments and completed work
- Track academic progress and grades
- View class timetables
- Manage account settings

## 🚀 Features

- **Multi-Platform**: Web and mobile applications
- **Offline Capability**: Mobile app works offline with automatic sync when online
- **Role-Based Access Control**: Different dashboards for Admin, Teacher, and Student
- **Student ID System**: Unique student ID for authentication
- **Class Management**: Students assigned to one class based on form level (1-6)
- **Teacher Subject Assignment**: Teachers assigned based on subjects they teach
- **Academic Tracking**: Comprehensive student academic records management
- **User-Friendly Interface**: Engaging, intuitive design for all user groups

## 📱 Technology Stack

### Backend
- **Framework**: Node.js/Express or Django
- **Database**: PostgreSQL/MySQL
- **Authentication**: JWT-based authentication with role-based authorization

### Frontend (Web)
- **Framework**: React.js or Vue.js
- **State Management**: Redux or Vuex
- **UI Library**: Material-UI or Ant Design

### Mobile
- **Framework**: React Native or Flutter
- **Offline Storage**: SQLite with sync mechanism
- **State Management**: Redux or Provider pattern

## 📁 Project Structure

```
zimbabwe-school-management-system/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── utils/
│   ├── tests/
│   ├── config/
│   └── package.json
├── frontend-web/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── styles/
│   └── package.json
├── mobile-app/
│   ├── src/
│   │   ├── screens/
│   │   ├── components/
│   │   ├── navigation/
│   │   └── services/
│   └── package.json
├── docs/
│   ├── API_DOCUMENTATION.md
│   ├── DATABASE_SCHEMA.md
│   ├── USER_GUIDES/
│   └── SETUP_GUIDE.md
└── README.md
```

## 🔐 User Roles & Permissions

### Administrator
- Full system access
- User management (create, edit, delete)
- School configuration
- Report generation
- Fee management

### Teacher
- View assigned classes
- Manage student academic records
- Create and distribute learning materials
- Track student progress
- View own profile and schedule

### Student
- View own records (read-only for personal info)
- Submit assignments
- View academic progress
- Access learning materials
- View schedule

## 📊 Database Entities

- **Users** (Admin, Teacher, Student)
- **Schools**
- **Classes** (Forms 1-6)
- **Students**
- **Teachers**
- **Subjects**
- **Assignments**
- **Notes/Learning Materials**
- **Tests**
- **Grades/Academic Records**
- **Fees/Payments**
- **Attendance**
- **Announcements**

## 🛠 Getting Started

### Prerequisites
- Node.js v14+ or Python 3.8+
- PostgreSQL/MySQL
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/Black-Pontiff/zimbabwe-school-management-system.git
cd zimbabwe-school-management-system
```

2. Set up the backend
```bash
cd backend
npm install
# Configure .env file
npm run start
```

3. Set up the frontend
```bash
cd ../frontend-web
npm install
npm start
```

4. Set up the mobile app
```bash
cd ../mobile-app
npm install
npm run android  # or npm run ios
```

## 📖 Documentation

- [API Documentation](./docs/API_DOCUMENTATION.md)
- [Database Schema](./docs/DATABASE_SCHEMA.md)
- [Setup Guide](./docs/SETUP_GUIDE.md)
- [User Guides](./docs/USER_GUIDES/)

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## 📄 License

This project is licensed under the MIT License - see [LICENSE](./LICENSE) file for details.

## 📞 Support

For issues, questions, or suggestions, please open an issue on GitHub or contact the development team.

---

**Last Updated**: September 2026
**Version**: 1.0.0-alpha
