# 🤖 InterviewIQ.ai - AI Interview Agent (MERN Stack)

**InterviewIQ.ai** is a comprehensive, AI-powered mock interview platform built using the MERN Stack. It acts as a realistic human interviewer that can evaluate candidates based on their resumes, roles, and experience. It listens to user answers via microphone, provides AI-driven feedback, scores candidates on confidence, communication, and correctness, and generates a downloadable PDF performance report.

---

## ✨ Features

* **Resume Analysis:** Upload a PDF resume, and the AI automatically extracts your roles, experience, projects, and skills to generate personalized interview questions.
* **Smart Voice Interview:** Experience a realistic interview simulation where the AI agent speaks questions out loud, and you can answer back using your microphone.
* **Adaptive Difficulty:** Questions are generated dynamically with varying difficulty levels (Easy, Medium, Hard).
* **Real-time Performance Evaluation:** AI evaluates your answers to provide feedback on:
    * Confidence
    * Communication
    * Correctness (Technical Accuracy)
* **Interview Modes:** Choose between **HR Interview** and **Technical Interview** modes.
* **Credit System & Payment Gateway:** Users start with free credits. Conducting an interview consumes credits. Seamlessly purchase more credits using the integrated **Razorpay** payment gateway.
* **Analytics & Reports:** View past interview history and download detailed performance reports in PDF format.
* **Authentication:** Secure Google OAuth login using Firebase.

---

## 🛠️ Tech Stack

**Frontend:**
* React.js (Vite)
* Tailwind CSS
* Framer Motion (Animations)
* Redux Toolkit (State Management)
* React Router DOM
* Axios
* Recharts (Data Visualization)
* JSPDF & JSPDF-Autotable (PDF Generation)
* Web Speech API (Speech-to-Text & Text-to-Speech)

**Backend:**
* Node.js & Express.js
* MongoDB Atlas & Mongoose
* JSON Web Tokens (JWT) & Cookie Parser (Auth)
* Multer (File Upload handling)
* PDF.js (Resume Parsing)
* OpenRouter API (LLM Integration - GPT-4o-mini)
* Razorpay API (Payment Processing)

---

## 🚀 Installation and Setup

### Prerequisites
* Node.js installed
* MongoDB Atlas Account
* OpenRouter API Key
* Razorpay Account (Test Mode)
* Firebase Project (for Google Auth)

