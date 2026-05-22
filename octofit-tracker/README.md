# OctoFit Tracker - Multi-Tier Application

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 with Vite
├── backend/           # Node.js + Express + TypeScript
└── README.md
```

## Ports Configuration

- **Frontend**: http://localhost:5173 (React Vite dev server)
- **Backend API**: http://localhost:8000 (Express.js server)
- **MongoDB**: mongodb://localhost:27017 (MongoDB database)

## Setup Instructions

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

### Backend Setup
```bash
cd backend
npm install
npm run dev
```

### Build for Production

**Frontend:**
```bash
cd frontend
npm run build
```

**Backend:**
```bash
cd backend
npm run build
npm start
```

## Technologies

### Frontend
- React 19
- Vite (Build tool)
- TypeScript

### Backend
- Node.js
- Express.js
- TypeScript
- Mongoose (MongoDB ODM)
- MongoDB

## Notes
- Ensure MongoDB is running on port 27017 before starting the backend
- Frontend runs on Vite's development server on port 5173
- Backend API server listens on port 8000
