# Creative Ideas Platform

A community-driven platform for sharing creative ideas, receiving feedback, and participating in knowledge exchange.

### Quick Start Guide

1. **Register** - Create your account with username, email, and password
2. **Login** - Access the platform with your credentials
3. **Browse Ideas** - Explore creative ideas from the community
4. **Submit Ideas** - Share your own creative concepts
5. **Engage** - Rate and provide feedback on ideas you find interesting
6. **Track Progress** - View your profile to see your contributions and stats

### Key Workflows

#### 💡 Submitting an Idea
1. Click "Submit Idea" button
2. Enter title (5-100 characters)
3. Write description (10-5000 characters)
4. Submit and share with community
5. Receive ratings and feedback from others

#### ⭐ Rating an Idea
1. Browse or search for ideas
2. Click on an idea to view details
3. Select 1-5 stars based on your evaluation
4. Rating is saved and contributes to average
5. Update your rating anytime

#### 💬 Providing Feedback
1. View idea details
2. Read existing feedback
3. Write your constructive feedback (min 10 characters)
4. Submit feedback
5. Feedback appears with your username and timestamp

#### 👤 Managing Profile
1. Click on profile icon/dropdown
2. View your statistics and activity
3. Edit profile information
4. Upload profile picture
5. View all your submitted ideas

## Project Structure

```
creative-ideas-platform/
├── backend/                 # Node.js + Express API
│   ├── src/
│   │   ├── middleware/     # Express middleware
│   │   ├── routes/         # API route handlers
│   │   ├── services/       # Business logic
│   │   ├── models/         # Data models and types
│   │   └── index.ts        # Application entry point
│   ├── package.json
│   └── tsconfig.json
│
└── frontend/               # React + TypeScript frontend
    ├── src/
    │   ├── components/     # React components
    │   ├── contexts/       # React contexts
    │   ├── hooks/          # Custom React hooks
    │   ├── services/       # API client services
    │   ├── App.tsx         # Main App component
    │   └── main.tsx        # Application entry point
    ├── package.json
    └── vite.config.ts
```

## Setup Instructions

### Quick Setup (Recommended)

Run the setup script to install all dependencies:

**Windows:**
```bash
setup.bat
```

**Linux/Mac:**
```bash
chmod +x setup.sh
./setup.sh
```

**Or using npm from root:**
```bash
npm run setup
```

### Manual Setup

#### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

The backend API will be available at `http://localhost:3000`

#### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

The frontend will be available at `http://localhost:5173`

### Running from Root Directory

You can also run the projects from the root directory:

```bash
# Start backend
npm run dev:backend

# Start frontend (in a separate terminal)
npm run dev:frontend
```

## Technology Stack

### Backend
- Node.js with Express
- TypeScript
- SQLite (better-sqlite3)
- JWT for authentication
- bcrypt for password hashing

### Frontend
- React 18
- TypeScript
- Vite
- React Router
- Axios for API calls
- IndexedDB for client-side storage

## Development

- Backend runs on port 3000
- Frontend runs on port 5173
- Frontend proxies API requests to backend during development

