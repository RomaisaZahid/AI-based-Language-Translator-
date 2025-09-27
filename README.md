# 🌍 Language Translator App

This is a Python-based desktop application that translates speech from one language to another. The app uses speech recognition to capture voice input, translates it using Google Translate, and reads out the translated text using text-to-speech.

---

## 🧠 Overview

The goal of this project is to provide a user-friendly way to break language barriers. It helps users speak in one language and hear the translation in another using a clean graphical interface.

---

## 🎯 Features

- 🎤 **Speech Recognition** – Converts your voice into text
- 🌐 **Language Translation** – Translates text into another language
- 🔊 **Text-to-Speech** – Reads out the translated text
- 🖼️ **User-Friendly GUI** – Built using Tkinter
- ✅ Supports major languages like English, Urdu, Arabic, French, German, and more

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Tkinter** – For GUI
- **SpeechRecognition** – To recognize voice input
- **googletrans** – For translating text between languages
- **gTTS (Google Text-to-Speech)** – For audio output
- **OS Module** – For handling audio playback

---

## 💻 System Requirements

- Python 3.6 or higher
- Microphone (for speech input)
- Speakers or headphones (for audio output)
- Internet connection (for using Google APIs)

---

## 📦 Installation

1. Make sure Python is installed on your system:  
   👉 [Download Python](https://www.python.org/downloads/)

2. Clone this repository or download the ZIP.

3. Open terminal / command prompt in the project folder and install the required libraries:

```bash
pip install SpeechRecognition googletrans==4.0.0-rc1 gTTS

🚀 How It Works

Select input and target languages from the dropdown menus.

Click the Start Listening button to record your voice.

Speak clearly into your microphone.

Click Stop & Translate to process the audio.

The app will show both original and translated text and play the translated speech.

🌍 Supported Languages

English

Urdu

Arabic

Spanish

French

German

Korean

Persian

Russian

Chinese

Italian

(More languages can be added easily in the code.)
⚠️ Error Handling

🛑 Displays messages if:

Microphone input fails

Speech isn't clear

Translation API fails

Language isn't selected
Acknowledgments

Google Speech Recognition API

Google Translate API

gTTS (Google Text-to-Speech)

Python & Tkinter community
