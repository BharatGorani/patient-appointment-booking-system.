🏥 Patient Appointment Booking System
📖 Overview
A full-stack web application to manage doctor-patient appointments seamlessly. Patients can register, log in, and book, reschedule, or cancel appointments. Doctors (Admins) can manage and update appointment statuses.

This project is built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) and secured using JWT authentication.

🚀 Tech Stack
🔧 Backend:
Node.js

Express.js

MongoDB

Mongoose

JWT (JSON Web Tokens)

Dotenv

🎨 Frontend:
React.js

React Router DOM

Context API

Tailwind CSS

🛠️ Setup Instructions
📦 Backend Setup
Navigate to the backend folder:
cd backend

Install dependencies:
npm install

Create a .env file in the backend/ directory with the following content:

ini
Copy
Edit
PORT=5000
MONGO_URI=mongodb://localhost:27017/appointmentdb
JWT_SECRET=your_jwt_secret_key
Start the backend server:
npm run dev

💻 Frontend Setup
Navigate to the frontend folder:
cd frontend

Install dependencies:
npm install

Start the frontend development server:
npm start

🌐 Usage
Open your browser and go to: http://localhost:3000

Sign up or log in as a Patient or Doctor

Patients can:

Book new appointments

Reschedule or cancel existing appointments

Doctors/Admins can:

View and manage all appointments
![Screenshot (939)](https://github.com/user-attachments/assets/ac10d3a3-b673-4ba3-82d3-a00dc856881b)
![Screenshot (940)](https://github.com/user-attachments/assets/5aedc94c-5897-444d-ab22-cd624ef06bf7)
![Screenshot (941)](https://github.com/user-attachments/assets/b042156a-e921-4e25-a4c1-9e09c71b35d1)




Change appointment statuses

