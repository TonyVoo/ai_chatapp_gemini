🤖 AI Chat App (Powered by Gemini API)
A real-time AI-powered chatbot built with Node.js, React, and Google's Gemini API for intelligent conversations.

🚀 Features
🔹 AI-Powered Responses – Chat with Gemini AI for intelligent answers
🔹 User Authentication – Secure login/signup with JWT
🔹 Real-time Chat – Interactive UI with instant responses
🔹 Message History – Save and view past conversations
🔹 Responsive UI – Mobile & desktop-friendly design
🛠 Tech Stack
Frontend: React.js, TailwindCSS
Backend: Node.js, Express.js
AI Model: Google Gemini API
Database: MongoDB (for storing chat history & users)
Authentication: JWT (JSON Web Token)

📦 Installation
1️⃣ Clone the repository

git clone [https://github.com/your-username/ai-chat-app.git](https://github.com/TonyVoo/ai_chatapp_gemini.git)

cd ai-chat-app

2️⃣ Install dependencies

# Backend

cd backend

npm install

# Frontend

cd ../frontend

npm install

3️⃣ Setup environment variables

Create a .env file in both frontend and backend folders.

Backend (backend/.env)

env

GEMINI_API_KEY=your-google-gemini-api-key

MONGO_URI=your-mongodb-connection-string

JWT_SECRET=your-secret-key

Frontend (frontend/.env)

env

REACT_APP_API_URL=http://localhost:5000

4️⃣ Run the app

Start the backend server

cd backend

npm run dev

Start the frontend

cd frontend

npm start

🚀 Your AI Chat App is now running! Open http://localhost:3000 in your browser.

🏗 API Endpoints

🔐 Authentication

POST /api/auth/register – Register a new user

POST /api/auth/login – Login user

GET /api/auth/user – Get user details

💬 Chat with AI

POST /api/chat – Send a message & get AI response

📜 Chat History

GET /api/chats – Fetch user’s chat history

🤝 Contributing

Contributions are welcome! Fork the repo and submit a pull request.
