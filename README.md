# 🎭 RealReveal – Deepfake Video Detection

> AI-powered deepfake video detection platform built with TensorFlow, OpenCV, InceptionV3, and GRU networks.

## 🚀 About The Project

RealReveal is a deep learning-based web application that detects manipulated (deepfake) videos by analyzing both visual and temporal patterns within video frames.

The system combines **InceptionV3** for spatial feature extraction and **GRU (Gated Recurrent Unit)** networks for temporal sequence learning, enabling accurate classification of videos as **REAL** or **FAKE**.

### ✨ Key Highlights

* 🎥 Deepfake Video Detection
* 🧠 CNN + RNN Hybrid Architecture
* ⚡ Real-Time Prediction
* 🔍 Frame-Level Feature Extraction
* 🌐 Web-Based User Interface
* 📊 81.25% Detection Accuracy

---

## 🏗️ Architecture

```text
Video Upload
      ↓
Frame Extraction
      ↓
Preprocessing
      ↓
InceptionV3
      ↓
GRU Network
      ↓
Dense Layer
      ↓
REAL / FAKE
```

---

## 🛠️ Tech Stack

| Category        | Technologies                |
| --------------- | --------------------------- |
| Language        | Python                      |
| Deep Learning   | TensorFlow, Keras           |
| Computer Vision | OpenCV                      |
| Data Processing | NumPy, Pandas, Scikit-Learn |
| Web Framework   | Flask                       |
| Frontend        | HTML, CSS, JavaScript       |

---

## 📈 Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 81.25% |
| Precision | 80%    |
| Recall    | 82%    |
| F1 Score  | 81%    |


## 🔄 Workflow

1. Upload a video.
2. Extract frames using OpenCV.
3. Preprocess and normalize frames.
4. Extract features using InceptionV3.
5. Analyze temporal patterns using GRU.
6. Predict whether the video is REAL or FAKE.
7. Display the result through the web application.

---

## 🎯 Future Improvements

* Real-Time Webcam Detection
* Audio Deepfake Detection
* Cloud Deployment
* Mobile Application
* Enhanced UI/UX with a more modern, responsive, and visually appealing frontend design

---
## 📖 Publication

This project is based on our research paper **"RealReveal: Bringing Deepfake Detection to the Web with Advanced Machine Learning"**, published in the **Baghdad Science Journal**.

The research presents a deep learning-based approach for DeepFake video detection using **InceptionV3** and **GRU** architectures, achieving **81.25% accuracy** on the DFDC dataset.

## 👨‍💻 Developed By

**Soumyadip Saha**

B.Tech in Information Technology
JIS College of Engineering

## 📖 Publication

This project is based on our research paper **"RealReveal: Bringing Deepfake Detection to the Web with Advanced Machine Learning"**, published in the **Baghdad Science Journal**.

The research presents a deep learning-based approach for DeepFake video detection using **InceptionV3** and **GRU** architectures, achieving **81.25% accuracy** on the DFDC dataset.

---

## 👨‍💻 Team

* Soumyadip Saha
* Md Dilshad Alam
* Suraj Sarkar
* Surajit Matia
* Arani Mishra

**Project Supervisor:** Mrs. Tanusree Saha

Department of Information Technology
JIS College of Engineering, Kalyani, West Bengal

---

## 🙏 Acknowledgements

We sincerely thank our project supervisor, **Mrs. Tanusree Saha**, and all team members for their guidance, support, and valuable contributions throughout the development and publication of this project.

---

⭐ If you found this project interesting, consider giving it a star!

