# Arabic Poetry AI Toolkit

An AI-powered toolkit for analyzing, generating, and enhancing Arabic poetry using Natural Language Processing (NLP) and Deep Learning techniques.

## Project Overview

This toolkit integrates multiple AI models that work together to explore Arabic poetry from different perspectives — from meter classification to audio enhancement and even automatic verse generation.

## Project Structure

Arabic-Poetry-AI-Toolkit/
├── 1_Meter_Classification/ # Classifies Arabic poetry meters using ML
├── 2_Audio_Enhancement/ # Enhances noisy poetry audio using U-Net
├── 3_Poetry_Generation/ # Generates new Arabic verses using Markovify
├── 4_Speaker_Identification/ # Identifies speaker voice from recordings
├── 5_Deploy_App/ # Flask backend for model deployment
└── 6_Web_Interface_HTML/ # Web interface (HTML/CSS/JS)

---

## Features

- Poetry Meter Classification — Detects the meter (بحر) of Arabic verses.
- Audio Enhancement (U-Net) — Improves sound clarity in poetry recitations.
- Poetry Generation — Generates original Arabic poetry lines.
- Speaker Identification — Identifies the reciter using deep learning.
- Flask Deployment — Web app for interacting with all models.

---

How to Run Locally

Install dependencies:

pip install -r requirements.txt

Run the Flask app:

python app.py

Open your browser at:
http://127.0.0.1:5000

Technologies Used

Python

Flask

TensorFlow / Keras

Markovify

Librosa (Audio Processing)

HTML, CSS, JavaScript

Author

Eman Muhamed
GitHub: EmanMuhamed

Future Improvements

Add transformer-based poetry generation (e.g., GPT models)

Enhance web UI with a modern design

Add dataset visualization tools

“Where Arabic language meets Artificial Intelligence”
