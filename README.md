# 🤖 DevTown Chatbot

An AI-powered chatbot built using FastAPI, LangChain, and Groq API.
This chatbot can store conversations and provide intelligent responses in real-time.

---

## 🚀 Live Demo

👉 https://devtown-chatbot.onrender.com/docs

---

## ✨ Features

* 💬 Real-time AI chatbot
* 🧠 Powered by LangChain + Groq
* 🗂️ MongoDB chat storage
* ⚡ FastAPI backend
* 🌐 Deployed on Render
* 📜 Interactive API docs (Swagger UI)

---

## 🛠️ Tech Stack

* Python
* FastAPI
* LangChain
* Groq API
* MongoDB
* Uvicorn
* Render (Deployment)

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/devtown-chatbot.git
cd devtown-chatbot
```

### 2. Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Setup environment variables

Create a `.env` file and add:

```
GROQ_API_KEY=your_api_key
MONGO_URI=your_mongodb_uri
```

### 5. Run the app

```bash
uvicorn app:app --reload
```

---

## 📡 API Endpoints

### Chat Endpoint

```
POST /chat
```

### Docs

```
GET /docs
```

---

## 📦 Deployment

Deployed on Render using:

```bash
uvicorn app:app --host 0.0.0.0 --port $PORT
```
---

## 👨‍💻 Author

**Pratham Danawala**

---

