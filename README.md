🧠 Mentora – AI-Powered Learning Management System

Mentora is a full-stack Learning Management System (LMS) designed to provide a scalable, secure, and intelligent learning platform. It enables seamless interaction between students and educators with AI-powered features for enhanced learning experiences.

🚀 Features

🔐 Authentication & Authorization

-> JWT-based secure login/signup

-> Role-based access (Student / Educator)

📚 Course Management

-> Create, update, and manage courses

-> Structured modules and lessons

💳 Payment Integration

-> Razorpay integration for course purchases

🤖 AI-Powered Search

-> Smart course discovery using AI (Gemini API)

📊 Dashboard

-> Personalized dashboards for students & instructors

⚡ Scalable Backend

-> Modular architecture with RESTful APIs

🛠️ Tech Stack

Frontend:

-React (Vite)

-Redux Toolkit

-Tailwind CSS

Backend:

-Node.js

-Express.js

-JWT Authentication

Database:

-MongoDB

Integrations:

-Razorpay API

-Gemini AI API

📁 Project Structure
Mentora/

│
├── client/ 

├── server/         # Backend (Node + Express)

├── models/         # MongoDB schemas

├── routes/         # API routes

├── controllers/    # Business logic

├── middleware/     # Auth & validations

└── config/         # DB & environment configs


⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/Rajat996-alt/mentora.git
cd mentora

2. Install dependencies
# For backend
cd server
npm install

# For frontend
cd ../client
npm install

3. Setup environment variables
Create a .env file in the server folder:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
RAZORPAY_KEY=your_key
GEMINI_API_KEY=your_api_key

4. Run the project
# Backend
cd server
npm run dev

# Frontend
cd client
npm run dev

🎯 Future Enhancements
   📈 Analytics & progress tracking
   🎥 Video streaming support
   🧑‍🤝‍🧑 Community / discussion forums
   📱 Mobile responsiveness improvements
   
🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

📬 Contact
Rajat Sen
Full Stack Developer (MERN)
📧 Connect on LinkedIn - www.linkedin.com/in/rajatsen13

⭐ Acknowledgement
If you found this project helpful, consider giving it a ⭐ on GitHub!
