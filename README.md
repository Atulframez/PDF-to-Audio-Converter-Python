# 📄🔊 PDF to Audio Converter (Python)

This project is a **Python-based PDF to Audio Converter** that reads text from a PDF file and converts it into an **MP3 audio file** using **Google Text-to-Speech (gTTS)**.

It is useful for **audio learning, accessibility, and hands-free reading**.
---
## 🚀 Features
- Extracts text from multi-page PDF files
- Converts PDF text into natural-sounding speech
- Generates MP3 audio output
- Simple and beginner-friendly Python script
- Useful for students and visually impaired users
---
## 🛠️ Technologies Used
- Python 3
- PyPDF2 (PDF text extraction)
- gTTS (Google Text-to-Speech)
- Requests & supporting libraries
---
## 📂 Project Structure
PDF-to-Audio-Converter-Python/
│
├── main.py # Main script
├── requirements.txt # Python dependencies
├── runtime.txt # Python version
├── name.pdf # Input PDF file
├── Audio.mp3 # Output audio file
└── README.md
---
## 📦 Installation
Install all required libraries using:
```bash
pip install -r requirements.txt
▶️ How to Use
Place your PDF file in the project folder
Rename it to name.pdf (or update filename in code)
Run the script:
bash
python main.py
The generated audio file will be saved as Audio.mp3
🔍 How It Works
Opens the PDF file
Reads text from each page
Combines extracted text
Converts text into speech using gTTS
Saves output as an MP3 file
🎯 Learning Outcomes
Working with PDF files in Python
Text-to-Speech conversion
File handling and automation
Building real-world utility scripts
⚠️ Notes
Requires an active internet connection (gTTS)
Works best with text-based PDFs (not scanned images)
👨‍💻 Author
Atul Anand
BCA (Hons), Amity University Noida
⭐ If you find this project useful, don’t forget to star the repository!
