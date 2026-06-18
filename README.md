<div align="center">

# 🧠⚡ AI Quiz Generator

<img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Flask-Web%20App-black?style=for-the-badge&logo=flask">
<img src="https://img.shields.io/badge/AI-Powered-purple?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">

### 🚀 Generate Intelligent MCQs instantly using AI (Claude API)

---

</div>

## 🌟 Overview

**AI Quiz Generator** is a modern full-stack web application built with **Flask + Anthropic Claude AI** that generates intelligent multiple-choice questions (MCQs) from any topic.

It validates topics, adjusts difficulty, and dynamically creates quizzes in real-time.

---

## ✨ Features

- 🧠 AI-powered MCQ generation (Claude API)
- 📚 Topic validation before quiz creation
- ⚡ Fast Flask backend API
- 🎯 Difficulty levels (Easy / Medium / Hard)
- 🔢 Custom question counts (5 / 10 / 15 / 20)
- 📊 Instant scoring system
- 🎨 Clean responsive UI
- 🔐 Secure API key handling

---

## 🏗️ Project Structure
quiz_app/
├── app.py # Flask backend server
├── requirements.txt # Python dependencies
├── templates/
│ └── index.html # Frontend UI
├── static/
│ ├── css/
│ │ └── style.css # UI styling & effects
│ └── js/
│ └── quiz.js # Frontend logic & API calls

---

## ⚙️ Setup & Installation

### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
## 2️⃣ Set API Key

Windows

set ANTHROPIC_API_KEY=your_api_key_here

Mac / Linux

export ANTHROPIC_API_KEY=your_api_key_here
## 3️⃣ Run Server
python app.py
## 4️⃣ Open Browser
http://localhost:5000
