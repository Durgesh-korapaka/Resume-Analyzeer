# 📄 Resume Analyzer

A full-stack application to **analyze resumes** using **LLMs (Gemini + LangChain)**.  
It extracts structured information (skills, experience, education, contact info, etc.), rates resumes, and suggests improvements + upskilling paths.  

## 🚀 Features
- **Upload & Analyze Resumes**
  - Upload PDF resumes
  - Extracts **structured fields** (name, email, phone, education, work experience, skills, etc.)
  - LLM-powered **resume rating, improvement areas, upskill suggestions**
  - Stores all data in **SQLite / Postgres**
- **History Tab**
  - View all past uploads in a clean table
  - Click **Details** to open a modal with full structured extraction
- **Frontend (React)**
  - Minimal, neat UI with two tabs (`Upload` and `History`)
  - Modal-based detail view
- **Backend (FastAPI)**
  - REST API endpoints
  - LLM integration (Gemini free tier via LangChain)
  - PDF parsing & structured extraction
- **Database**
  - Default: SQLite
  - Optional: Postgres support

---

## 🛠️ Tech Stack
- **Frontend:** React + Tailwind
- **Backend:** Python (FastAPI)  
- **Database:** SQLite (default), Postgres (optional)  
- **LLM:** Gemini (via LangChain)  
- **PDF Parsing:** pdfplumber  

---

## 📂 Project Structure
