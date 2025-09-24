# 📚 Full-Stack LMS Project

A complete **Learning Management System (LMS)** built with a **MERN stack**:

- **Frontend**: React 18, Vite, TailwindCSS, Redux Toolkit, Radix UI
- **Backend**: Node.js, Express.js, MongoDB, JWT Authentication, Cloudinary

This project supports **user authentication, course & lecture management, profile updates, and media uploads**, with a modern UI and fully responsive design.

---

## 🌍 Live Demo
#make you can login  offical account with your credentials then you go admin if you go directly admin you will not accessable 
- **Official Site**: [LMS Project](https://learning-management-system-lms-mern.onrender.com/)
- **Admin Dashboard**: [Admin Panel](https://learning-management-system-lms-mern.onrender.com/admin)

---

## 🚀 Features

### 🔑 Authentication

- Secure Login & Signup (JWT-based, HTTP-only cookies)
- Role-based access control (Student / Instructor / Admin)
- Logout functionality

### 👤 User Management

- Profile update (name, description, image upload to Cloudinary)
- View user profile

### 🎓 Course Management

- Create, update, delete courses
- Upload & update course thumbnails
- View all published courses
- View instructor’s courses
- Course details page

### 🎥 Lecture Management

- Add, edit, delete lectures
- Upload videos (Cloudinary)
- Preview lecture feature
- Fetch all lectures of a course

### 🛠️ Admin Dashboard

- Manage courses and lectures
- Manage users
- Nested routes (`/admin/dashboard`, `/admin/course`, etc.)

### 🎨 Frontend Features

- Modern UI with **TailwindCSS** + Radix UI + ShadCN
- Persistent state with **redux-persist**
- Responsive design (mobile-first)

---

## 🛠️ Tech Stack

### Frontend

- React 18 + Vite
- React Router v7 (`createBrowserRouter`, `RouterProvider`)
- Redux Toolkit + Redux Persist
- TailwindCSS + Radix UI + ShadCN components
- React Quill (rich text editor)
- React Player (video player)
- Lucide React & React Icons

### Backend

- Node.js, Express.js
- MongoDB + Mongoose
- JWT + bcrypt (authentication)
- Multer + Cloudinary (file uploads)
- dotenv (environment variables)

---



PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
