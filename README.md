📄 Resume Analyzer & ATS Optimizer

This project is a Flask web application that helps users analyze, evaluate, and optimize their resumes against a given job description. It uses Natural Language Processing (NLP), OCR, and AI (Google Gemini API) to extract resume content, evaluate job matching, and generate ATS-friendly resumes in .docx format.

🚀 Features

Upload Resume (PDF/Image) → Extracts text using PyMuPDF or OCR (Tesseract).

Job Description Input → Paste a JD to analyze match.

Resume Evaluation → Highlights strengths, weaknesses, matching & missing skills.

Match Score → Calculates similarity score between resume & JD using TF-IDF + Cosine Similarity.

Resume Improvement → Uses Gemini AI to generate a one-page ATS-optimized resume.

DOCX Resume Generator → Exports improved resume as a .docx file with formatting.

Feedback Learning → Updates ML model (Logistic Regression) with feedback.

🛠️ Tech Stack

Backend: Flask (Python)

AI Model: Google Gemini API (gemini-2.0-flash)

ML/NLP:

Scikit-learn (TF-IDF, Logistic Regression)

Cosine Similarity for JD-resume matching

OCR & PDF Handling:

PyMuPDF (fitz)

Tesseract OCR (pytesseract)

pdf2image

Document Generation: python-docx

Frontend: HTML + Jinja2 Templates
