# Career Guide - Server

This is the backend server for the Career Guide application. It provides RESTful APIs for career data, user authentication, reviews, and related functionality.

---

## Technologies Used

- **Node.js**  
- **Express.js**  
- **MongoDB Atlas** (NoSQL database)  
- **Firebase Authentication** (for user auth and token verification)  
- **JWT** (JSON Web Tokens for API security)  
- **dotenv** (for environment variables)  
- **CORS** (Cross-Origin Resource Sharing)  
- **Nodemon** (for development)

---

## Project Files

/controllers
/middleware
/models
/routes
/firebase-admin-service-key.json
/.env
/server.js
/package.json

- `controllers/` - Request handlers for different API endpoints  
- `middleware/` - Middleware for auth and error handling  
- `models/` - Mongoose schemas and models  
- `routes/` - API route definitions  
- `firebase-admin-service-key.json` - Firebase Admin SDK service key file  
- `.env` - Environment variables file (DB credentials, JWT secrets)  
- `server.js` - Main Express server setup and startup  
- `package.json` - Project dependencies and scripts

---

## Screenshot

![App Screenshot](https://i.ibb.co/93Htf93f/Screenshot-2025-06-24-124608.png)

---

## How to Run Locally

1. Clone the repository  
2. Run `npm install`  
3. Create a `.env` file with your config variables  
4. Start the server using `npm start` or `nodemon server.js` (for development)

---

## Author

Md Raihan Uddin

---

