# 🚗 Automatic Number Plate Recognition (ANPR)

## 📌 Overview
This project implements a computer vision pipeline to **detect and extract vehicle license plate numbers** from images.  
It is designed to work with license plates containing **English alphabets and numeric characters**, and performs reliably across different scenarios.

The system follows a two-stage approach:
- A **localization model** is used to detect and crop the license plate region from the input image.
- The cropped plate is then processed using **Tesseract OCR** to recognize and extract the text.

---

## ⚙️ Setup & Execution

### 1. Create Environment
```bash
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate
