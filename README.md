# Language Translator App

This is a Python-based desktop application that translates speech from one language to another. The app uses speech recognition to capture voice input, translates it using Google Translate, and reads out the translated text using text-to-speech.

## Overview

The purpose of this project is to provide an accessible way to break language barriers. It allows users to speak in one language and hear the translation in another using a simple graphical interface.

## Features

- Speech Recognition – Converts voice into text
- Language Translation – Translates the recognized text into another language
- Text-to-Speech – Converts translated text into speech
- Graphical User Interface – Built using Tkinter
- Supports multiple popular languages

## Technologies Used

- Python 3.x
- Tkinter – For the GUI
- SpeechRecognition – For capturing and processing audio input
- googletrans – For translating text
- gTTS (Google Text-to-Speech) – For generating speech from text
- os module – For audio playback handling

## System Requirements

- Python 3.6 or higher
- Microphone (for speech input)
- Speakers or headphones (for audio output)
- Internet connection (for API access)

## Installation

1. Install Python from: https://www.python.org/downloads/

2. Download or clone this repository.

3. Open a terminal or command prompt in the project directory and run:
python language_translator.py

## How It Works

Select the input language and the target language from dropdown menus.

Click the "Start Listening" button to begin voice capture.

Speak into your microphone clearly.

Click the "Stop & Translate" button to process the audio.

The app will display the original and translated text and play the translated speech aloud.


## Supported Languages

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

(More languages can be added by modifying the language mapping in the code.)

## Error Handling

Displays error messages if:

Microphone access fails

Speech is not detected

Selected language is not supported

Google API request fails
```bash
pip install SpeechRecognition googletrans==4.0.0-rc1 gTTS
