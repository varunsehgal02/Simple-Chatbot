# Simple Chatbot

A modern chatbot built with React (frontend) and Python Flask (backend). This chatbot supports:
- **Chat history** with a daily record.
- **A 'New Chat' button** to reset conversations.
- **A sleek, dark-themed UI** for a better experience.

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/varunsehgal02/Simple-Chatbot.git
cd Simple-Chatbot
```

### 2️⃣ Backend Setup (Flask API)
```sh
cd backend
pip install -r requirements.txt
```
- **Set up the API key** in `.env`:
  ```sh
  echo "GROQ_API_KEY=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" > .env
  ```
- **Run the backend server**:
  ```sh
  python app.py
  ```

### 3️⃣ Frontend Setup (React UI)
```sh
cd frontend/chatbotui
npm install
npm run dev
```

## 🎯 How to Use
- Click on the **History Icon** 📜 to view past chats.
- Click on **New Chat** ➕ to start a fresh conversation.
- Enter your message and chat in real-time!

## 📜 Technologies Used
- **Frontend**: React, Tailwind CSS, React Icons
- **Backend**: Flask, OpenAI API (Groq API)

## 🌟 Features
- **Chat History:** View conversations by date.
- **New Chat Page:** Start fresh chats without refreshing.
- **Modern UI:** Sleek and user-friendly design.

Enjoy your chatbot! 🚀

