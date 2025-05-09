# Hollywood Celebrity Image Classification Project
This repository classifies celebrity face using traditional ML algorithm.
![Screenshot 2025-04-15 220447](https://github.com/user-attachments/assets/34422923-85f2-45a0-a863-c49cc78f9adc)

# 🎬 Celebrity Face Classifier

Welcome to the **Celebrity Face Classifier** – a machine learning project that predicts which celebrity is in the uploaded image using computer vision and pre-trained ML models.

## 📌 Project Overview

This Streamlit app uses face detection, feature extraction (Wavelets + HOG), and classification using trained machine learning models to recognize celebrities from images.

### 👤 Celebrities Included
Each celebrity in the dataset has **100 images** used to train the model:

- Angelina Jolie  
- Brad Pitt  
- Jennifer Lawrence  
- Johnny Depp  
- Megan Fox  
- Robert Downey Jr  
- Sandra Bullock  
- Tom Cruise  
- Tom Hanks  
- Will Smith

## 🧠 Models Used

- **Logistic Regression**
- **Support Vector Machine (SVM)**  

## 🛠️ Features

- Face + Eye detection (must detect **at least 2 eyes** to proceed)
- HOG + Wavelet-based feature extraction
- Streamlit web interface
- Upload any face image and get a prediction!

![Original Image](https://github.com/user-attachments/assets/0b1ad7a7-0901-4555-8f43-afb448e13da7)

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/celebrity-face-classifier.git
cd celebrity-face-classifier

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Streamlit app
streamlit run app.py
