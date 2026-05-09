# 📂 Dobby Drive - Backend API

This is the Node.js/Express backend for the Dobby Drive cloud storage system. It handles authentication, folder structures, and image metadata using MongoDB Atlas.

## 🚀 Deployment Info
- **Live API URL:** `https://dobby-assignment-backend.onrender.com`
- **Database:** MongoDB Atlas (Cloud)
- **Host:** Render

## 🛠️ Tech Stack
- Node.js & Express.js
- Mongoose (MongoDB ODM)
- JWT (JSON Web Tokens) for Auth
- Multer (for handling file uploads)

## 🔑 Environment Variables
To run this locally, create a `.env` file in the root:
```env
MONGO_URI=mongodb+srv://dobby_db:ATqqlCFLbIfxFIcW@cluster0.fl1u6n2.mongodb.net/?appName=Cluster0
JWT_SECRET=raza_secret_key_123