# Malik Family Care Clinic - Hospital Management System

A comprehensive hospital management system built with React, TypeScript, Node.js, and Electron.

## Features

### 🏥 Complete Hospital Management
- **Reception Module**: Patient registration, appointments, billing (ER/IPD)
- **Doctor Module**: Patient consultations, prescriptions, medical history
- **Lab Module**: Test management, reports, tracking
- **Pharmacy Module**: Inventory, POS, prescriptions, supplier management
- **Admin Module**: User management, system settings, reports

### 💻 Technology Stack
- **Frontend**: React 19, TypeScript, TailwindCSS, Vite
- **Backend**: Node.js, Express, MongoDB
- **Desktop**: Electron
- **PDF Generation**: jsPDF, auto-table
- **Charts**: Recharts
- **Icons**: Lucide React

## Quick Start

### Prerequisites
- Node.js (v18 or higher)
- MongoDB (local or cloud)
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/mindspire-org/Malik-Family-Care-Clinic.git
cd Malik-Family-Care-Clinic
```

2. Install dependencies:
```bash
npm install
cd backend && npm install
```

3. Set up environment:
```bash
# Copy .env.example to .env and configure
cp backend/.env.example backend/.env
```

4. Start development servers:
```bash
npm run dev
```

This will start:
- Frontend: http://127.0.0.1:3000
- Backend API: http://127.0.0.1:5000
- Electron desktop app

## Deployment

### Web Deployment (Vercel/Netlify)
1. Build the frontend:
```bash
npm run build:front
```

2. Deploy the `dist` folder to your hosting platform

### Backend Deployment (Railway/Heroku)
1. Build the backend:
```bash
npm run build:backend
```

2. Deploy the `backend` folder

### Desktop Application
```bash
npm run dist:win
```

## Project Structure
```
├── src/                 # React frontend
│   ├── pages/          # Page components
│   ├── components/     # Reusable components
│   ├── utils/          # Utility functions
│   └── types/          # TypeScript definitions
├── backend/            # Node.js backend
│   ├── src/           # Backend source code
│   └── dist/          # Compiled backend
├── electron/           # Electron main process
└── public/            # Static assets
```

## License
MIT License - see LICENSE file for details

## Support
For support and queries, please open an issue on GitHub.
