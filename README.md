# File Processing and Q&A Flask App

This is a Flask-based web application that processes various file types (PDF, Excel, Word documents, and text files) and uses Google Generative AI (`gemini-1.5-pro` model) to answer questions based on the content of the uploaded files.

---

## Features

- **File Support**:
  - PDF files (`.pdf`)
  - Microsoft Excel files (`.xlsx`, `.xls`)
  - Microsoft Word files (`.docx`)
  - Text files (`.txt`)

- **Question Answering**:
  - Extracts content from uploaded files.
  - Uses Google Generative AI to answer user-provided questions based on the extracted file content.

- **Error Handling**:
  - Displays user-friendly error messages for unsupported file formats or processing failures.

---

## Requirements

- **Programming Language**: Python 3.8 or above
- **Libraries**:
  - Flask
  - PyPDF2
  - openpyxl
  - python-docx
  - langchain-google-genai
  - python-dotenv

---
