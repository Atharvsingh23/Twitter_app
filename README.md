# 🐦 Twitter Clone

A full-stack Twitter clone built with **React.js**, **MongoDB**, and **Tailwind CSS**.  
This project mimics core Twitter features like posting tweets, user authentication, likes, and responsive design.

---

## 🚀 Features
- 🔐 User Authentication (Signup/Login)
- 📝 Post Tweets with text & media
- ❤️ Like & Unlike tweets
- 👤 User Profile with bio & posts
- 📱 Responsive UI using Tailwind CSS
- 🌐 REST API with MongoDB backend

---

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Authentication:** JWT (JSON Web Tokens)

---

## 📂 Project Structure
twitter-clone/
│── client/ # React.js frontend
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # App pages (Home, Profile, Login, etc.)
│ │ ├── App.js
│ │ └── index.js
│── server/ # Express backend
│ ├── models/ # MongoDB models
│ ├── routes/ # API routes
│ ├── controllers/ # Request handlers
│ └── server.js
│── package.json
│── README.md



Install dependencies
Frontend
cd client
npm install

Backend
cd ../server
npm install

Setup Environment Variables

Create a .env file inside the server folder:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

 Run the project
Start Backend
cd server
npm start

Start Frontend
cd client
npm start
