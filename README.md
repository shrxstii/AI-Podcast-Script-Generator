# podcast-episode-script-generator

An AI-powered podcast script generation platform that helps users create engaging and structured podcast episode scripts automatically using Generative AI.
The project combines a Python backend with a modern frontend interface to simplify podcast content creation for creators, students, and beginners.

---

# Features

* AI-generated podcast episode scripts
* User-friendly frontend interface
* FastAPI/Uvicorn backend integration
* Gemini API integration for content generation
* Modular project structure
* Frontend and backend separation
* API testing support
* Beginner-friendly implementation

---

# Tech Stack

* Python
* FastAPI
* Uvicorn
* HTML
* CSS
* JavaScript
* Gemini API
* Jupyter Notebook

---

# Project Structure

```bash
podcast-episode-script-generator/
│
├── frontend/              # Frontend files
├── notebook/              # Experiment notebooks
├── src/                   # Backend source code
├── tests/                 # Testing files
│
├── requirements.txt
├── test_gemini.py
├── README.md
└── .gitignore
```

---

# Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/Nikki31Chaudhary/podcast-episode-script-generator.git
```

## 2. Navigate to the Project Directory

```bash
cd podcast-episode-script-generator
```

## 3. Create Virtual Environment

```bash
python3 -m venv .venv
```

---

# Activate Virtual Environment

## For Mac/Linux

```bash
source .venv/bin/activate
```

## For Windows

```bash
.venv\Scripts\Activate.ps1
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
GOOGLE_API_KEY=YOUR_API_KEY
```

---

# Run Backend Server

```bash
uvicorn src.main:app --reload
```

Backend will run on:

```bash
http://127.0.0.1:8000
```

---

# Run Frontend

```bash
cd frontend
python -m http.server 5500
```

Frontend will run on:

```bash
http://127.0.0.1:5500
```

---

# How It Works

1. User enters a podcast topic.
2. Frontend sends request to backend API.
3. Gemini API generates podcast script.
4. Generated script is displayed on the frontend.

---

# Example Use Cases

* Podcast content generation
* AI-assisted storytelling
* Educational podcast creation
* Script drafting for creators
* Student AI mini projects

---

# Future Improvements

* Voice generation support
* Multi-language podcast scripts
* Download scripts as PDF
* Authentication system
* Podcast episode history
* Dark mode UI improvements

---

# Authors

* Shristi Upadhyay
* Nikki Chaudhary

---

# License

This project is created for educational and learning purposes.

---

# GitHub Repository

[podcast-episode-script-generator](https://github.com/Nikki31Chaudhary/podcast-episode-script-generator?utm_source=chatgpt.com)


# podcast-episode-script-generator
## Quick Start



# frontend
cd frontend
python -m http.server 5500
