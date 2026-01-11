# 📚 Learning Management System (LMS)

A full-stack Learning Management System (LMS) designed to manage online courses, video lectures, users, payments, and AI-powered search.
This project was developed as part of my hands-on learning journey to understand how real-world LMS platforms are built using modern web technologies.

------------------------------------------------------------

🚀 Project Overview

The Learning Management System (LMS) allows users to:

🔐 Register and log in securely  
📘 Browse free and paid courses  
🔍 Search courses using text or voice input  
🎥 Watch lecture videos stored in the cloud  
💳 Purchase courses using an online payment gateway  
👨‍💼 Manage courses (admin functionality)

This project integrates frontend, backend, cloud services, payments, email security, and AI APIs into a single complete application.

------------------------------------------------------------

🛠️ Tech Stack Used

Frontend: 
```text
HTML  
CSS  
Tailwind CSS  
JavaScript  
React.js
```

Backend:
```
Node.js  
Express.js  
```
Database:
MongoDB (MongoDB Atlas – Cloud Database)

Cloud, AI & Services:
Cloudinary – Video & lecture storage  
Razorpay (Test Mode) – Online payment gateway  
Gemini API – AI-powered course search & speech recognition  
Email Service (App Password / Passkey) – Secure email authentication  

Tools:
Git & GitHub  
VS Code  
Postman  

------------------------------------------------------------

✨ Key Features

🔐 User authentication (Signup & Login)  
👨‍🎓 Student & Admin roles  
📚 Course management  
🎥 Video lectures stored securely on Cloudinary  
🔍 AI-powered course search using Gemini API  
🎙️ Voice-based search (Speech-to-Text)  
💳 Razorpay payment integration (Test Mode)  
📧 Secure email setup using app password  
☁️ Cloud-based database (MongoDB Atlas)  
📱 Responsive user interface  
🔄 REST API architecture  

------------------------------------------------------------

🤖 Gemini API Integration (AI Search & Speech Recognition)

Integrated Gemini API to enhance course discovery.

Users can search courses using:
- Text input
- Voice input (speech converted to text)

Gemini processes the input and returns relevant course suggestions.
This improves usability and simulates AI-assisted learning platforms.

------------------------------------------------------------

🎥 Cloudinary Integration (Lecture Storage)

Lecture videos are uploaded to Cloudinary.
Only secure video URLs are stored in MongoDB.
This reduces backend server load and ensures fast, scalable video streaming.

------------------------------------------------------------

💳 Razorpay Payment Gateway (Test Mode)

Razorpay is integrated in test mode.
It supports secure course purchase flow.
Order creation and payment verification are handled on the backend.
The system is ready to switch to live mode in the future.

------------------------------------------------------------

📧 Email Authentication (App Password)

Email service is configured using an app password / passkey.
This avoids storing actual email passwords and improves security.
It can be used for notifications and account-related emails.

------------------------------------------------------------

📁 Project Structure

```text
LMS/
│
├── client/        Frontend (React)
├── server/        Backend (Node + Express)
├── models/        MongoDB schemas
├── routes/        API routes
├── controllers/   Business logic
├── config/        DB, Cloudinary, Razorpay, Gemini configs
├── .env           Environment variables
└── README.md

```

------------------------------------------------------------

⚙️ How to Run the Project Locally

Clone the repository:
```git clone https://github.com/Bharathi-2206/LMS.git```

Navigate to the project folder:
cd LMS

Backend setup:
```
cd backend
npm install
npm run dev
```

Frontend setup:
```
cd client
npm install
npm start
```

------------------------------------------------------------

🔐 Environment Variables

Create a .env file inside the backend folder and add:
```
PORT=8000

MONGODB_URL=your_mongodb_connection_string

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RAZORPAY_KEY_ID=your_test_key_id
RAZORPAY_KEY_SECRET=your_test_key_secret

GEMINI_API_KEY=your_gemini_api_key

EMAIL_USER=your_email
EMAIL_PASS=your_email_app_password
```
------------------------------------------------------------

🚀 Future Enhancements

Personalized AI course recommendations  
Razorpay live payment mode  
Course progress tracking  
Certificates generation  
Voice-based navigation  
Admin analytics dashboard  

------------------------------------------------------------

👩‍💻 Author

Lekireddy Bharathi  
Final Year CSE Student  

GitHub: https://github.com/Bharathi-2206

------------------------------------------------------------

⭐ Acknowledgement

This project was developed through self-learning, experimentation, and hands-on practice to understand how modern Learning Management Systems work.
