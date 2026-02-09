# 📰 AI-Powered News Summarizer & Voice Reader

An advanced **AI-driven full-stack web application** that fetches **live online news**, performs **intelligent text summarization using NLP**, supports **multi-language translation**, and provides a **voice-based news reader** with playback controls.

This project focuses on **fast information consumption, accessibility, and hands-free interaction**, making it suitable for real-world deployment, academic evaluation, and resume-grade showcasing.

---

## 📖 Table of Contents
- Overview
- Key Features
- Technology Stack
- System Architecture
- Detailed Workflow
- AI & NLP Pipeline
- Project Structure
- Installation & Cloning
- Configuration
- Running the Application
- Testing
- Error Handling
- Use Cases
- Future Enhancements
- License

---

## 🔍 Overview

With the rapid growth of digital news, users often struggle to read long articles.  
This system solves that problem by automatically summarizing news articles, translating them into multiple languages, and converting text into natural voice narration.

The application follows a **modular client-server architecture**, ensuring scalability, maintainability, and clean separation of concerns.

---

## ✨ Key Features

- AI-based news summarization
- Multi-language translation
- Voice reader (Text-to-Speech)
- Playback controls (Play / Pause / Stop)
- Interactive and responsive UI
- Robust error handling

---

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask (REST API)

### AI & NLP
- NLP-based summarization
- Translation engine
- Text-to-Speech (TTS)

---

## 🏗️ System Architecture

User → Frontend UI → Flask Backend → News API → AI Summarizer → Translator → TTS

---

## 🔄 Detailed Workflow

1. User selects news category and language
2. Frontend sends request to backend
3. Backend fetches news articles
4. Text preprocessing and summarization
5. Optional translation
6. Voice generation
7. Results displayed in UI

---

## 🤖 AI & NLP Pipeline

- Text preprocessing and cleaning
- Summarization using NLP models
- Language translation
- Voice synthesis using TTS

---

## 📂 Project Structure

<img width="778" height="528" alt="image" src="https://github.com/user-attachments/assets/974c2756-cc09-439b-b48a-9ff398c7ec6e" />

---

## 📥 Installation & Cloning

```bash
git clone https://github.com/<your-username>/ai-news-summarizer.git
cd ai-news-summarizer
```

Create virtual environment and install dependencies:

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r backend/requirements.txt
```

---

## ⚙️ Configuration

Add API key in `backend/config.py`:

```python
NEWS_API_KEY = "your_api_key_here"
```

---

## ▶️ Running the Application

```bash
cd backend
python app.py
```

Open browser:
```
http://127.0.0.1:5000
```

---

## 🧪 Testing

```bash
pytest tests/
```

---

## ⚠️ Error Handling

- API failures handled gracefully
- No-news scenarios supported
- Fallback when TTS fails

---

## 🎯 Use Cases

- Students & researchers
- Busy professionals
- Visually impaired users
- AI & NLP learning projects
- Resume and portfolio showcase

---

## 🚀 Future Enhancements

- Mobile app
- Cloud deployment
- User authentication
- Advanced AI models
- Emotion-based voice narration
