# 🛒 AI-Powered Grocery Shopping Chatbot

An intelligent grocery shopping chatbot built using **Python (FastAPI)** and **OpenAI**, with **Firebase** and **Spoonacular API** integration. This bot helps users find grocery products, manage a shopping cart, and receive live updates — all through natural language.

---

## 🚀 Features

- 🤖 Chatbot powered by **OpenAI GPT-3.5**
- 🛍 Grocery item search via **Spoonacular API**
- 🔥 **Firebase Firestore** for cart storage
- 🧠 Context-aware shopping suggestions
- 🔄 Real-time cart update support with **WebSockets**
- 📦 Planned frontend with React or Streamlit

---

## 🧱 Tech Stack

| Layer         | Tech Used                |
|--------------|--------------------------|
| Backend       | Python, FastAPI          |
| Chat Engine   | OpenAI GPT-3.5           |
| Grocery Data  | Spoonacular API          |
| Database      | Firebase Firestore       |
| Realtime Updates | FastAPI WebSockets or Firebase |
| Authentication | (Coming soon) Firebase Auth |
| Frontend      | (Coming soon) Streamlit or React |

---

## 📁 Folder Structure

grocery_chatbot/ ├── main.py # FastAPI app ├── chat.py # OpenAI chatbot logic ├── grocery_api.py # Spoonacular grocery search ├── firebase_service.py # Firebase Firestore connection ├── firebase_key.json # Firebase credentials (not committed) ├── .env # API keys (ignored in Git) ├── requirements.txt # Dependencies └── README.md # This file
