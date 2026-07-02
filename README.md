# 🏥 Healthcare Medical Report AI Assistant using Generative AI

> An AI-powered healthcare assistant that extracts, analyzes, summarizes, and explains medical reports using OCR and Large Language Models (LLMs).

![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![Gemini](https://img.shields.io/badge/Gemini-API-orange)
![OCR](https://img.shields.io/badge/OCR-EasyOCR%20%7C%20Tesseract-red)
![React](https://img.shields.io/badge/React-Frontend-61DAFB)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 📖 Overview

Healthcare Medical Report AI Assistant is an end-to-end AI-powered application that helps users understand their medical reports through Generative AI.

The system extracts text from uploaded PDF or image-based medical reports using OCR, analyzes clinical information with Google's Gemini API, generates easy-to-understand summaries, highlights abnormal values, and allows users to ask natural language questions about their reports.

This project demonstrates practical applications of:

- Generative AI
- Prompt Engineering
- OCR Pipelines
- Healthcare AI
- REST API Development
- End-to-End AI Application Development

---

# ✨ Features

## 📄 Medical Report Upload

- Upload PDF reports
- Upload scanned reports
- Upload laboratory reports
- Upload prescription images

---

## 🔍 OCR Processing

- Extract text from scanned documents
- Preserve report formatting
- Support multiple medical report formats
- Convert images into structured text

---

## 🤖 AI Medical Summary

Generate patient-friendly summaries from complex medical reports.

### Example

### Input

```
Hemoglobin: 9.8 g/dL
```

### AI Output

> Your hemoglobin level is lower than the normal range, which may indicate anemia. Please consult your physician for further evaluation.

---

## 💬 Chat with Your Medical Report

Users can ask questions such as:

- What diseases are mentioned?
- Explain my blood test.
- Is my cholesterol normal?
- What medicines are prescribed?
- What should I discuss with my doctor?
- Summarize my diagnosis.
- Explain medical terms in simple language.

---

## ⚠️ Highlight Abnormal Test Values

Automatically detects abnormal laboratory values.

| Test | Result | Status |
|-------|---------|--------|
| Hemoglobin | 9.8 g/dL | 🔴 Low |
| Cholesterol | 240 mg/dL | 🔴 High |
| Vitamin D | 18 ng/mL | 🔴 Low |

---

## 📊 Dashboard

- Previous uploads
- AI-generated summaries
- Report history
- Download AI summary
- User activity

---

## 🔐 Security

- Secure file uploads
- JWT Authentication
- User Login
- Protected APIs
- Temporary file storage

---

# 🏗️ System Architecture

```
                User
                  │
                  ▼
        Upload Medical Report
                  │
                  ▼
      OCR (EasyOCR / Tesseract)
                  │
                  ▼
       Extract Structured Text
                  │
                  ▼
          FastAPI Backend
                  │
                  ▼
     Gemini API (LLM Analysis)
        ┌─────────┼──────────┐
        ▼         ▼          ▼
   Summary   Explanation   Chatbot
                  │
                  ▼
          React Frontend
```

---

# 🛠️ Tech Stack

## AI & NLP

- Google Gemini API
- Prompt Engineering
- Natural Language Processing (NLP)

## Backend

- Python
- FastAPI
- REST APIs

## OCR

- EasyOCR
- Tesseract OCR

## Data Processing

- Pandas
- NumPy

## Database

- MySQL
- MongoDB

## Frontend

- React.js
- HTML5
- CSS3
- JavaScript

## Deployment

- Docker
- GitHub

---

# 🚀 Advanced Features

✅ AI-generated Medical Summary

✅ Medical Terminology Explanation

✅ Drug Information Lookup

✅ Disease Risk Summary

✅ Follow-up Question Generation

✅ Report Chatbot

✅ Abnormal Test Detection

✅ Multi-language Support (English & Tamil)

✅ Voice Input

✅ Voice Response

✅ Medical History Timeline

✅ Download AI Summary as PDF

---

# 🔮 Future Enhancements

- Retrieval-Augmented Generation (RAG)
- FAISS / ChromaDB Vector Database
- Medical Guideline Retrieval
- Doctor Recommendation Module
- Appointment Scheduling
- Medical Report Comparison
- Cloud Deployment
- Mobile Application
- HIPAA-inspired Security Enhancements

---

# 📂 Project Structure

```
Healthcare-AI-Assistant/

│── backend/
│   ├── api/
│   ├── services/
│   ├── models/
│   ├── utils/
│   ├── OCR/
│   ├── prompts/
│   └── main.py
│
│── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
│
│── uploads/
│
│── database/
│
│── docker/
│
│── requirements.txt
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Healthcare-AI-Assistant.git
```

```
cd Healthcare-AI-Assistant
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

Activate

### Windows

```bash
venv\Scripts\activate
```

### Linux/Mac

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Configure Environment Variables

Create a `.env` file.

```
GEMINI_API_KEY=YOUR_API_KEY

JWT_SECRET=YOUR_SECRET

DATABASE_URL=YOUR_DATABASE_URL
```

---

## Run FastAPI

```bash
uvicorn main:app --reload
```

---

## Run React

```bash
npm install

npm start
```

---

# 📸 Screenshots

### Dashboard

*(Add Screenshot Here)*

---

### Upload Medical Report

*(Add Screenshot Here)*

---

### AI Summary

*(Add Screenshot Here)*

---

### Chat Interface

*(Add Screenshot Here)*

---

# 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Large Language Models (LLMs)
- Google Gemini API Integration
- Prompt Engineering
- OCR Pipelines
- FastAPI Backend Development
- REST API Design
- AI Chatbot Development
- React Frontend Development
- Full Stack AI Applications
- Healthcare AI Solutions

---

# 📈 Resume Highlights

This project showcases expertise in:

- Generative AI
- Prompt Engineering
- OCR-Based Document Intelligence
- Healthcare AI
- NLP Applications
- API Integration
- Backend Engineering
- Full Stack Development
- AI-powered Chat Systems

---

# ⚠️ Disclaimer

This application is intended **for educational and informational purposes only**.

It **does not provide medical advice, diagnosis, or treatment** and should not be considered a substitute for consultation with qualified healthcare professionals.

---

# 👨‍💻 Author

**Dhanush A**

📧 Email: your-email@example.com

🔗 LinkedIn: https://linkedin.com/in/yourprofile

💻 GitHub: https://github.com/yourusername

🌐 Portfolio: https://yourportfolio.com

---

⭐ If you found this project useful, consider giving it a star!
