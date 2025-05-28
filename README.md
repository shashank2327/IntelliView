# 🧠 AI Interview Prep Web App

An AI-powered interview preparation web app built with **Node.js**, **Express**, **MongoDB**, **React**, and **Gemini API**. This app allows users to create customized interview sessions and receive AI-generated questions and answers tailored to their role, experience level, and focus areas.

---

## 🚀 Features

- 🔐 **User Authentication** – Secure registration and login
- 🧩 **Custom Interview Sessions** – Based on:
  - Role (e.g., Software Developer, Product Manager)
  - Experience level (e.g., Fresher, Mid-Level, Senior)
  - Topics to focus on (e.g., Data Structures, System Design)
  - Number of questions
- 🤖 **Gemini API Integration** – AI-generated interview questions and model answers
- 📈 **Session History** – Track and review past sessions
- 💬 **Interactive Q&A Interface** – Real-time question and answer view
- 🎯 **Clean, Responsive UI** – Built with React

---

## 🛠 Tech Stack

**Frontend:**
- React
- Tailwind CSS / Bootstrap (optional)
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- Gemini API

---

## 📦 Installation

### 1. Create a .env file in /backend with the following
- JWT_SECRET=your_jwt_secret_key
- MONGO_URI=your_mongodb_connection_string
- GEMINI_API_KEY=your_gemini_api_key
- PORT=5000

### 2. Backend Setup
```bash
cd backend
npm install
```
- Start the backend server:
```bash
nom run dev
```

### 2. Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```

