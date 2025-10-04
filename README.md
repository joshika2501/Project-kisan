🌾 Krishi Saathi – Smart AgriTech Platform

Krishi Saathi is an AI + IoT powered AgriTech solution designed to support farmers with crop disease detection, fertilizer recommendations, multilingual chatbot assistance, and real-time agricultural decision-making.
The platform integrates Machine Learning, IoT sensors, and multilingual conversational AI to ensure sustainable farming and higher productivity.

🚀 Features

🌱 Crop Disease Detection – Deep Learning (CNN) & ML models for early-stage detection.

🧪 Fertilizer Packet Scanning & Calculator – OCR + ML to analyze fertilizer composition & provide optimal dosage.

🗣️ Chatbot with Multilingual Voice Support – Farmers interact via voice/text in Indian languages.

🛰️ Location & Advisory – Google Maps API for geo-tagging & advisory.

🔒 Secure Auth System – Firebase integration for farmer accounts.

📊 Sensor Data Integration – Real-time IoT sensor data (NPK, temperature, humidity, gas).

🛠️ Tech Stack
1. Language & Environment

Python – Core ML/DL development

Jupyter Notebook / VS Code – Development environment

2. ML/DL for Disease Detection

TensorFlow / Keras – CNN model training & saving (.h5)

Scikit-learn – Experimentation (RandomForest, DecisionTree, etc.)

Splitfolders – Dataset splitting

NumPy, Pandas – Data handling

3. Data Preprocessing & Augmentation

ImageDataGenerator (Keras) – Image rescaling & augmentation

4. Chatbot & Multilingual Voice Support (Prototype)

gTTS – Text-to-speech

SpeechRecognition / Google Speech API – Voice input

IndicNLP / AI4Bharat – Multilingual NLP support for Indian languages

5. Storage & Model Handling

Local File System – Dataset + trained model (disease_model.h5)

Frontend

React (with TypeScript) – UI framework

Tailwind CSS – Styling & responsiveness

Backend

Node.js – API & server-side logic

FastAPI – ML model serving

Database

PostgreSQL – Farmer data, crop & advisory storage

Authentication

Firebase + Firestore – Secure user authentication & cloud database

Miscellaneous

Ruby i18n Library – Multilingual support

Google Maps API – Location-based advisory

Web Speech API – Real-time browser voice support

Fertilizer Packet Scanning & Calculator

Language: Python

Core Libraries: Pandas, NumPy, Scikit-learn

Computer Vision: OpenCV, Pytesseract (Tesseract OCR)

Model: Random Forest Classifier

Platform: Google Colab

Dataset: Synthetic + Real-time sensor data

Error Handling: thefuzz (for typo/error detection in fertilizer names)
Demo Workflow

 Farmer uploads/voices crop disease query.

 Model analyzes and predicts disease.

 Fertilizer packet scanned → OCR → composition extracted.

 Fertilizer calculator suggests optimized dosage.

 Chatbot explains results in local language (voice/text).

 Location-based insights shared via Google Maps API.
 
