# 🏥 Doctor Appointment Booking System

A full-stack web application built using the **MERN stack (MongoDB, Express, React, Node.js)** that allows patients to book appointments with doctors, and doctors to manage their schedules efficiently.

---

## 🚀 Features

### 👤 Patient Features
- User Registration & Login (JWT Auth)
- View list of available doctors by specialization
- Book appointments based on doctor availability
- View upcoming & past appointments
- Cancel appointments

### 🩺 Doctor Features
- Doctor Registration & Login
- Set availability (days & time slots)
- View scheduled appointments
- Accept/Reject appointment requests

### 🛠 Admin Features (Optional)
- Manage users and doctors
- View all appointments
- Manage specializations

## 🧱 Tech Stack

A modern full-stack web application built using the MERN stack, integrated with image upload and payment processing features.

### 🖥️ Frontend
- **React.js** – Building dynamic user interfaces
- **Tailwind CSS** – Utility-first styling
- **Axios** – For making HTTP requests to the backend
- **React Router DOM** – For routing between pages

### ⚙️ Backend
- **Node.js + Express.js** – RESTful API server
- **Mongoose** – MongoDB object modeling and schema management
- **JWT (jsonwebtoken)** – Authentication for patients and doctors
- **bcryptjs** – Password hashing and verification
- **dotenv** – Environment variable management

### 🗃️ Database
- **MongoDB Atlas** – Cloud-based NoSQL database for storing users, doctors, appointments

### ☁️ File Uploads
- **Cloudinary** – Storing and retrieving profile images and documents
- **Multer** *(optional)* – Handling multipart/form-data uploads to server

### 💳 Payments
- **Razorpay API** – Payment gateway integration for booking paid appointments

### 🧰 Developer Tools
- **Nodemon** – Hot-reloading during backend development
- **CORS** – Handling cross-origin requests
- **Postman** – API testing tool

### 🔧 Setup Backend

cd backend

npm install

--- npm run start 

### Create a .env file and add:

# 🛢️ MongoDB Atlas URI
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/doctor-app

# 🔐 JWT Secret
JWT_SECRET=your_jwt_secret_key

# ☁️ Cloudinary Config

CLOUDINARY_CLOUD_NAME=your_cloud_name

CLOUDINARY_API_KEY=your_api_key

CLOUDINARY_API_SECRET=your_api_secret


# 💳 Razorpay Config

RAZORPAY_KEY_ID=your_razorpay_key_id

RAZORPAY_KEY_SECRET=your_razorpay_key_secret


### 🔧 Setup FrontEnd

cd frontend

npm install

npm run dev


### 🔧 Setup Admin

cd Admin

npm install

npm run dev


