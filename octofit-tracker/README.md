# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

```
octofit-tracker/
├── frontend/          # React 19 + Vite (Port 5173)
├── backend/           # Express + TypeScript (Port 8000)
└── README.md
```

## Ports

- **Frontend:** 5173
- **Backend API:** 8000
- **MongoDB:** 27017

## Quick Start

### Frontend
```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

### Backend
```bash
cd octofit-tracker/backend
npm install
npm run dev
```

### MongoDB
Ensure MongoDB is running on port 27017:
```bash
mongod --port 27017
```

## Stack

- **Frontend:** React 19, Vite, TypeScript
- **Backend:** Express.js, TypeScript, Mongoose ODM
- **Database:** MongoDB
- **Runtime:** Node.js 18+

## Next Steps

1. Install dependencies in both frontend and backend directories
2. Configure environment variables in backend `.env` file
3. Start MongoDB service
4. Run backend and frontend development servers
