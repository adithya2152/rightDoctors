# RIGHT DOCTORS ASSIGNMENT

A simple CRUD application built with the MERN stack (MongoDB, Express.js, React, Node.js) to manage people records.

## Features

- View all people in a responsive grid layout
- Add new person with form validation
- Edit existing person details
- Delete person with confirmation
- Search people by name
- Filter people by gender
- Responsive design for all devices

## Tech Stack

**Frontend:**
- React with TypeScript
- Tailwind CSS for styling
- React Router for navigation
- Axios for API calls
- Lucide React for icons

**Backend:**
- Node.js with Express
- MongoDB with Mongoose
- CORS for cross-origin requests
- Dotenv for environment variables

## Project Structure

```
rightdoctors/
├── frontend/          # React frontend application
├── backend/           # Node.js + Express backend
└── README.md         # Project documentation
```

## Getting Started

1. Clone the repository
2. Install dependencies for both frontend and backend:
   ```bash
   cd frontend && npm install
   cd ../backend && npm install
   ```
3. Create a `.env` file in the backend directory with:
   ```
   MONGO_URI=your_mongodb_connection_string
   PORT=5000
   ```
4. Start the development servers:
   ```bash
   # Terminal 1 - Start backend
   cd backend
   npm run dev

   # Terminal 2 - Start frontend
   cd frontend
   npm run dev
   ```

## API Endpoints

- `GET /api/person` - Get all people
- `GET /api/person/:id` - Get single person
- `POST /api/person` - Create new person
- `PUT /api/person/:id` - Update person
- `DELETE /api/person/:id` - Delete person

## Data Model

Person:
- name (String, required)
- age (Number, required)
- gender (String, enum: ['Male', 'Female', 'Other'])
- mobile (String, required, 10 digits)
# rightDoctors
