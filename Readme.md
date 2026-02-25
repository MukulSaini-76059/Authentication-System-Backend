# 🚀 Authentication System – Backend

This is the backend of a Full Stack Authentication System built using **Node.js, Express, and MongoDB**.  
It provides secure user authentication using **JWT**, password hashing with **bcrypt**, and Google OAuth integration.

---


## 🔧 Features

- User Registration
- User Login
- Password Hashing using Bcrypt
- JWT Authentication
- Protected Routes
- Google Authentication
- Environment Variables for Security
- Error Handling
- MongoDB Database Integration
- Deployed on Render

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- JSON Web Token (JWT)
- Bcrypt
- Google OAuth
- dotenv
- Render (Deployment)

---

## 📡 API Endpoints

### Register User
POST /api/register

### Login User
POST /api/login

### Google Authentication
POST /api/google-auth

### Protected Dashboard
GET /api/dashboard  
(Requires JWT Token in Authorization Header)

---

## ⚙️ Installation & Setup

### 1. Clone the repository
git clone https://github.com/MukulSaini-76059/Backend.git

### 2. Navigate to project folder
cd Backend

### 3. Install dependencies
npm install

### 4. Create `.env` file and add:

PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_secret_key  
GOOGLE_CLIENT_ID=your_google_client_id  

### 5. Run the server
npm run dev

or

node server.js

---

## 📂 Project Structure

backend/
│── controllers/  
│── models/  
│── routes/  
│── middleware/  
│── config/  
│── server.js  

---

## 🔗 Frontend Repository

Frontend GitHub:  
https://github.com/MukulSaini-76059/Frontend

Live Frontend:  
https://frontend-seven-indol-27.vercel.app

---

## 👨‍💻 Author

**Mukul**  
Aspiring Full Stack Developer 🚀
