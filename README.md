# User CRUD API

A simple REST API to Create, Read, Update, and Delete users. Built with Node.js, Express, and MongoDB.

Built for the Syntecxhub Back-End Internship — Project 1.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Copy `.env.example` to `.env` and add your MongoDB connection string:
PORT=5000
MONGO_URI=your_mongodb_connection_string


3. Run the server:
```bash
npm run dev
```

---

## API Endpoints

Base URL: `http://localhost:5000/api/users`

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/users` | Create a user |
| GET | `/api/users` | Get all users |
| GET | `/api/users/:id` | Get one user |
| PUT | `/api/users/:id` | Update a user |
| DELETE | `/api/users/:id` | Delete a user |

**Example request body (POST/PUT):**
```json
{
  "name": "John Doe",
  "email": "John@example.com",
  "age": 22
}
```

