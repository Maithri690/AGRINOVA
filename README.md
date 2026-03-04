# 🌾 Rythu Mithra – Smart Agriculture Assistant

## 📌 Overview

**Rythu Mithra** is an AI-powered smart agriculture assistant built to support farmers with crop guidance, weather insights, expense tracking, and AI-based plant disease detection.

The application integrates modern technologies like **Streamlit**, **Google Gemini AI**, speech recognition, and geolocation services to provide intelligent and user-friendly farming assistance.

---

## 🚀 Features

### 🌱 1. AI Crop Advisory

* Farmers can ask agricultural questions in natural language.
* Powered by **Google Gemini AI**.
* Provides intelligent crop suggestions, fertilizer guidance, and farming best practices.

### 🌦️ 2. Weather Information

* Fetches real-time weather data using APIs.
* Helps farmers plan irrigation and harvesting.
* Uses geolocation for location-based weather updates.

### 🧾 3. Expense Tracker

* Record farming expenses.
* View structured data using pandas.
* Helps in farm budget management.

### 🖼️ 4. Plant Disease Detection (Image Analysis)

* Upload crop images.
* AI analyzes and provides possible disease identification and remedies.

### 🎤 5. Voice Interaction

* Speech-to-text using `SpeechRecognition`
* Text-to-speech using `pyttsx3`
* Enables accessibility for rural users

---

## 🛠️ Tech Stack

| Component         | Technology Used                     |
| ----------------- | ----------------------------------- |
| Frontend          | Streamlit                           |
| AI Model          | Google Gemini (google-genai SDK)    |
| Backend Logic     | Python                              |
| Data Handling     | Pandas                              |
| Image Processing  | Pillow                              |
| Voice Support     | SpeechRecognition, PyAudio, pyttsx3 |
| Location Services | Geocoder                            |
| API Requests      | Requests                            |

---

## 📂 Project Structure

```
RYTHU-MITHRA/
│
├── app.py
├── requirements.txt
├── .venv/
├── .streamlit/
│   └── secrets.toml
└── README.md
```

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/rythu-mithra.git
cd rythu-mithra
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv .venv
```

Activate:

**Windows (PowerShell):**

```bash
.venv\Scripts\Activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install streamlit pillow requests pandas geocoder speechrecognition pyaudio pyttsx3 google-genai
```

---

## 🔑 Environment Variable Setup (Important)

Create a Gemini API key from:
👉 https://aistudio.google.com/app/apikey

Set environment variable (PowerShell):

```bash
$env:GEMINI_API_KEY="YOUR_API_KEY"
```

Or permanently add it in Windows Environment Variables.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The app will open in your browser at:

```
http://localhost:8501
```

---

## 🎯 Target Users

* Farmers
* Agriculture Students
* Rural Entrepreneurs
* Agri-Tech Developers

---

## 🔐 Security Note

Never hardcode your API keys in the source code.
Always use environment variables or `.streamlit/secrets.toml`.

---

## 🌟 Future Enhancements

* Multi-language support (Telugu, Hindi, English)
* Government scheme recommendations
* Crop yield prediction
* Soil health analysis
* Mobile app version

---

## 👩‍💻 Developed By

**Uppari Maithri**
B.Tech – AI & ML
Narsimha Reddy Engineering College

---

## 📜 License

This project is for educational and research purposes.

---

### 🌾 “Empowering Farmers with AI Intelligence”
    
