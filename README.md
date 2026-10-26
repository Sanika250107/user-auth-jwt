# User Authentication & JWT

A beginner-friendly User Authentication API built using Node.js, Express.js, MongoDB, and JSON Web Tokens (JWT).

## Features

- User registration
- Secure password hashing using bcrypt
- User login
- JWT-based authentication using HTTP-only cookies
- Protected user profile route
- User logout
- MongoDB database integration

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- bcryptjs
- Cookie Parser

## API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/` | Check API status |
| GET | `/api/auth/test` | Test authentication routes |
| POST | `/api/auth/register` | Register a new user |
| POST | `/api/auth/login` | Log in |
| GET | `/api/auth/profile` | View protected user profile |
| POST | `/api/auth/logout` | Log out |

## Run Locally

1. Install dependencies:

   `npm install`

2. Create a `.env` file and configure `PORT`, `MONGO_URI`, `JWT_SECRET`, and `NODE_ENV`.

3. Start the server:

   `npm run dev`

4. Open `http://localhost:3000`.

**Security:** Never upload your `.env` file or expose your database credentials and JWT secret.
