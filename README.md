# 🎶 Music Genre Classification

This project provides a complete **end-to-end solution for music genre classification**, combining deep learning with an intuitive web interface.  
A Convolutional Neural Network (CNN) was trained on the **GTZAN dataset** and deployed as a **Streamlit web application**, allowing users to upload audio files and receive real-time predictions.

---

## 📌 Project Overview

- **Dataset:** [GTZAN Music Genre Dataset](http://marsyas.info/downloads/datasets.html)  
  Contains **1000+ audio tracks** across 10 genres (classical, jazz, hip hop, rock, etc.).  
- **Workflow:** Data preprocessing → CNN model training → Evaluation → Web deployment.  
- **Web App:** User-friendly interface for uploading `.mp3` files and classifying genres instantly.  

---

## ✨ Key Features

- **Advanced Deep Learning Model**  
  - Trained a CNN on Mel spectrograms (visual representation of audio).  
  - 50 training epochs with the Adam optimizer.  
  - Achieved **95.27% training accuracy** and **94.86% validation accuracy**.  
  - Loss converged to **0.1378 (train)** and **0.1705 (val)** → stable, well-generalized model.  

- **Robust Audio Preprocessing**  
  - Converts raw audio into Mel spectrograms.  
  - Captures both spectral and temporal characteristics → highly effective for CNN-based classification.  

- **Interactive Web Application**  
  - Built with **Streamlit**.  
  - Users can upload their own `.mp3` files.  
  - Provides real-time predictions from 10 possible genres.  
  - Example: correctly predicted a test audio file as **rock**.  

---

## 📂 Project Structure

