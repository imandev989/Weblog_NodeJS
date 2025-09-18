# 📝 Weblog – Node.js Blog Platform

A simple **weblog (blogging platform)** built with **Node.js**, **Express.js**, and **EJS templates**.  
This project demonstrates core concepts like authentication, session handling, and CRUD operations with MongoDB.  

---

## 🚀 Features

- **Authentication System**  
  - User registration & login  
  - Password hashing with bcryptjs  
  - Session management with express-session  
  - Flash messages (success/error notifications)  

- **Blog Management**  
  - Create, edit, and delete blog posts  
  - View all posts on the homepage  
  - Each post has its own dedicated page  

- **Validation** with Yup  
- **Template Rendering** with EJS + express-ejs-layouts  
- **Environment Configuration** using dotenv  
- **Logging** with Morgan  
- **Role-based Access Control** (extendable for Admin/Users)  

---

## 🛠 Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB + Mongoose  
- **View Engine:** EJS + express-ejs-layouts  
- **Authentication:** Passport.js (local strategy), bcryptjs  
- **Session & Flash Messages:** express-session, connect-flash  
- **Validation:** Yup  
- **Environment Config:** dotenv  

---

## 📂 Project Structure (example)


weblog_nodejs/
│── app.js # Entry point
│── config/ # Database & passport config
│── models/ # Mongoose models (User, Post, etc.)
│── routes/ # Express routes (auth, blog, dashboard)
│── controllers/ # Business logic for routes
│── middlewares/ # Authentication & validation
│── views/ # EJS templates (pages, layouts, partials)
│── public/ # Static files (CSS, JS, images)
│── .env # Environment variables
└── package.json



---

## ⚡ Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/imandev989/Weblog_NodeJS.git
cd Weblog_NodeJS
npm install

PORT=5000
MONGO_URI=mongodb://localhost:27017/weblog
SESSION_SECRET=your_secret_key

# Development
npm run dev

# Production
npm start

Server will start at:
👉 http://localhost:5000
```



