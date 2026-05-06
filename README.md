# 📚 AI Story Generator  
### Flask + NLP + Generative AI API

---

## 🚀 Project Overview
The AI Story Generator is a web application that creates creative stories from user input prompts using Artificial Intelligence (NLP + Generative AI API).  

It takes a simple idea from the user and converts it into a complete meaningful story using an AI model integrated with a Flask backend.

---

## ✨ Features
- AI-based story generation from prompts  
- NLP processing for better understanding  
- Flask web application  
- Simple and responsive UI  
- Fast API response system  
- Multiple story generation support  

---

## 🛠️ Tech Stack
- Frontend: HTML, CSS, JavaScript  
- Backend: Python (Flask)  
- AI/NLP: OpenAI / Gemini API  
- Libraries: Flask, requests, python-dotenv, nltk (optional)

---

## 📁 Project Structure
AI-Story-Generator/
│
├── app.py                  # Main Flask application  
├── requirements.txt        # Dependencies  
├── .env                    # API key file  
│
├── templates/  
│   └── index.html          # Frontend UI  
│
├── static/  
│   ├── style.css           # CSS styling  
│   └── script.js           # JavaScript logic  
│
├── utils/  
│   └── story_generator.py  # AI API logic  
│
└── README.md               # Documentation  



## ⚙️ Installation

### 1. Clone Repository
```bash
git clone https://github.com/mohsinjutt-313/ai-story-generator.git
cd ai-story-generator

### 2. Create Virtual Environment

python -m venv venv

### 3. Activate Environment

Windows:

venv\Scripts\activate

### 4. Install Dependencies
pip install -r requirements.txt

🔑 API Setup

Create a .env file and add:

API_KEY=your_api_key_here

### ▶️ Run Project
python app.py

### Open browser:

http://127.0.0.1:5000/

### 🧠 How It Works

User prompt → Flask backend → AI API → Story generation → Display on UI

### 📦 Requirements

flask

requests

python-dotenv

nltk

### 🚀 Future Improvements

Voice input

PDF download story

Story categories

Login system

Multi-language support
