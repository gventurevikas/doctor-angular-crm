# Ankur App - HIPAA Compliant Medical Application

This is a HIPAA-compliant Angular application designed for medical professionals to manage patient care, appointments, and medical records securely.

## Features

### Medical Management
- **Patient Management**: Complete patient records and history
- **Appointment Scheduling**: Advanced appointment booking and management
- **Electronic Health Records (EHR)**: Secure patient data management
- **Prescription Management**: Digital prescription creation and tracking
- **Telehealth**: Video consultations and remote patient care

### Administrative
- **Billing & Insurance**: Medical billing and insurance claim processing
- **Reports & Analytics**: Medical analytics and reporting
- **Doctor Profile**: Professional profile and credential management
- **Settings**: Application configuration and preferences

### Security & Compliance
- **HIPAA Compliance**: Full compliance with healthcare privacy regulations
- **Service Worker**: Offline functionality and data caching
- **Encrypted Data**: All patient data is encrypted in transit and at rest
- **Audit Logging**: Complete audit trail for all data access

## Technology Stack

- **Framework**: Angular 20
- **State Management**: NgRx Store
- **UI Framework**: Bootstrap 5 + ng-bootstrap
- **Charts**: Chart.js + ng2-charts
- **Icons**: FontAwesome
- **Medical Standards**: FHIR Kit Client
- **Real-time**: Socket.io
- **PDF Processing**: PDF.js

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn

### Installation
```bash
npm install --legacy-peer-deps
```

### Development
```bash
npm start
```

### Production Build
```bash
npm run build:prod
```

### Testing
```bash
npm test
```

## Security Considerations

- All API calls use HTTPS
- Patient data is encrypted using industry-standard encryption
- Session management with automatic timeout
- Role-based access control
- Comprehensive audit logging
- Regular security updates and patches

## Deployment

This application is designed for deployment in secure healthcare environments with proper HIPAA compliance measures in place.

## License

This project is proprietary and confidential. All rights reserved.
