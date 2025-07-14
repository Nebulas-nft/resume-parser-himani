# resume-parser-himani
# 📝 Automated Resume Parser

This Python project extracts key information from PDF resumes using **pdfplumber** and **spaCy**, and stores the data into an **SQLite database** for easy access and searching.

## 👩‍💻 Built by
**Himani Chugh**  
Codec Technologies – 1-Month Python Developer Internship

## 🎯 Project Objective

> Parse resumes to identify and save entities such as names, education details, organizations, locations, and dates.

## 📂 Features

- Extract full text from PDF resumes using `pdfplumber`
- Detect named entities like `PERSON`, `ORG`, `GPE`, `DATE` with `spaCy`
- Save extracted data to `SQLite` database (`resume_data.db`)
- Beginner-friendly code with clear structure

## 🛠 Requirements

- Python 3.13
- pdfplumber
- spaCy
- en_core_web_sm model (for spaCy)
- SQLite (built into Python)

## 🚀 How to Run

1. Clone the repo or download the files
2. Save your resume as `resume.pdf` in the same folder
3. Run the script:
   ```bash
   python resume_parser_with_db.py
