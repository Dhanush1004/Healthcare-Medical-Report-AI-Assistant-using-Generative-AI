# Healthcare Medical Report AI Assistant using Generative AI

> An AI-powered healthcare assistant that extracts, analyzes, summarizes, and explains medical reports using OCR and Large Language Models (LLMs).

![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![Gemini](https://img.shields.io/badge/Gemini-API-orange)
![OCR](https://img.shields.io/badge/OCR-EasyOCR%20%7C%20Tesseract-red)
![React](https://img.shields.io/badge/React-Frontend-61DAFB)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## Overview

Healthcare Medical Report AI Assistant is an AI-powered web application that helps users understand their medical reports using Generative AI. The application extracts text from uploaded PDF or image-based reports using OCR, analyzes the content with Google's Gemini API, generates patient-friendly summaries, explains complex medical terminology, highlights abnormal values, and answers natural language questions related to the uploaded report.

This project demonstrates practical applications of:

- Generative AI
- Prompt Engineering
- OCR Pipelines
- Healthcare AI
- REST API Development
- Full-Stack AI Application Development

---

## Features

### Medical Report Upload

- Upload PDF medical reports
- Upload scanned reports
- Upload laboratory reports
- Upload prescription images

### OCR Processing

- Extract text from scanned medical reports
- Preserve report structure
- Support multiple report formats
- Convert images into structured text

### AI Medical Summary

Generate easy-to-understand summaries from complex medical reports.

**Example**

**Input**

```text
Hemoglobin: 9.8 g/dL
```

**AI Output**

> Your hemoglobin level is lower than the normal range, which may indicate anemia. Please consult your physician for further evaluation.

---

### Chat with Your Medical Report

Users can ask questions like:

- What diseases are mentioned?
- Explain my blood test.
- Is my cholesterol normal?
- What medicines are prescribed?
- What should I discuss with my doctor?
- Explain this report in simple language.
- Summarize my diagnosis.

---

### Highlight Abnormal Test Values

| Test | Result | Status |
|------|--------|--------|
| Hemoglobin | 9.8 g/dL | Low |
| Cholesterol | 240 mg/dL | High |
| Vitamin D | 18 ng/mL | Low |

---

### Dashboard

- Previous uploads
- AI-generated summaries
- Report history
- Download AI summary
- User activity

---

### Security

- Secure file uploads
- JWT Authentication
- Protected REST APIs
- Temporary file storage

---

## System Architecture

```text
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

## Tech Stack

### Artificial Intelligence

- Google Gemini API
- Prompt Engineering
- Natural Language Processing (NLP)

### Backend

- Python
- FastAPI
- REST APIs

### OCR

- EasyOCR
- Tesseract OCR

### Data Processing

- Pandas
- NumPy

### Database

- MySQL
- MongoDB

### Frontend

- React.js
- HTML5
- CSS3
- JavaScript

### Deployment

- Docker
- GitHub

---

## Advanced Features

- AI-generated medical summaries
- Medical terminology explanation
- Drug information lookup
- Disease risk summary
- Follow-up question generation
- Intelligent report chatbot
- Automatic abnormal test detection
- Multi-language support (English & Tamil)
- Voice input
- Voice response
- Medical history timeline
- Download AI summary as PDF

---

## Future Improvements

- Retrieval-Augmented Generation (RAG)
- FAISS / ChromaDB Vector Database
- Medical guideline retrieval
- Doctor recommendation module
- Appointment scheduling
- Medical report comparison
- Cloud deployment
- Mobile application
- Enhanced security and privacy

---

## Project Structure

```text
Healthcare-AI-Assistant/
│
├── backend/
│   ├── api/
│   ├── services/
│   ├── models/
│   ├── prompts/
│   ├── ocr/
│   ├── utils/
│   └── main.py
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── App.js
│
├── uploads/
├── database/
├── docker/
├── requirements.txt
├── .env.example
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/Healthcare-AI-Assistant.git

cd Healthcare-AI-Assistant
```

### Create a Virtual Environment

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file.

```env
GEMINI_API_KEY=YOUR_API_KEY
JWT_SECRET=YOUR_SECRET_KEY
DATABASE_URL=YOUR_DATABASE_URL
```

### Run Backend

```bash
uvicorn main:app --reload
```

### Run Frontend

```bash
npm install
npm start
```

---

## Screenshots

### Dashboard

> Add screenshot here

### Upload Medical Report

> Add screenshot here

### AI Summary

> Add screenshot here

### Chat Interface

> Add screenshot here

---

## Learning Outcomes

This project demonstrates experience with:

- Large Language Models (LLMs)
- Google Gemini API Integration
- Prompt Engineering
- OCR Pipelines
- FastAPI Backend Development
- REST API Design
- AI Chatbot Development
- React.js Development
- Full-Stack AI Applications
- Healthcare AI Solutions

---

## Resume Highlights

This project showcases expertise in:

- Generative AI
- Prompt Engineering
- OCR-Based Document Intelligence
- Healthcare AI
- Natural Language Processing
- API Integration
- Backend Engineering
- Full-Stack Development
- AI-powered Conversational Systems

---

## Disclaimer

This application is intended for **educational and informational purposes only**.

It **does not provide medical advice, diagnosis, or treatment** and should not be considered a substitute for consultation with qualified healthcare professionals.

---

## Author

**Dhanush A**

- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile
- Portfolio: https://yourportfolio.com

---

## License

This project is licensed under the MIT License.

---

If you found this project useful, consider giving it a ⭐.
