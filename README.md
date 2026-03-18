# Clinic Appointment System (MERN)

A full-stack Clinic Appointment System built using the MERN stack that enables patients to book, manage, and track appointments online, while allowing doctors to efficiently manage schedules and availability.

# Features
- User authentication (Login/Register)
- Book, update, and cancel appointments
- Doctor scheduling and availability management
- Real-time appointment tracking
- Responsive user interface

# Tech Stack
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- API: RESTful APIs

# Project Structure
clinic-appointment-system/
│── client/        # React frontend  
│── server/        # Node/Express backend  
│── models/        # Database schemas  
│── routes/        # API routes  
│── controllers/   # Business logic  

# Installation & Setup

# 1. Clone the repository
git clone https://github.com/prajwal0129/clinic-appointment-system.git  
cd clinic-appointment-system  

# 2. Install dependencies
# Backend  
cd server  
npm install  

# Frontend  
cd ../client  
npm install  

# 3. Run the project
# Start backend  
cd server  
npm start  

# Start frontend  
cd ../client  
npm start  

# Environment Variables
Create a `.env` file in the server folder and add:

MONGO_URI=your_mongodb_connection_string  
PORT=5000  
JWT_SECRET=your_secret_key  

# Future Enhancements
- Payment integration  
- Email/SMS notifications  
- Admin dashboard  
- AI-based appointment recommendations  

# Author
Prajwal P Kedlaya
