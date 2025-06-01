# 🧠 Parkinson’s Disease Detection with mmWave Radar

This project implements a deep learning-based system to detect signs of Parkinson's disease using arm tremor patterns captured by mmWave radar.

The goal is to classify whether a subject shows signs of Parkinsonian tremors based on movement data processed into Doppler images.

---

## 📡 Project Overview

- **Data Source**: Real-time radar signals collected via Texas Instruments mmWave sensor (IWR1443BOOST)
- **Signal Processing**: FFT, range-Doppler transformation using MATLAB and OpenCV
- **Model**: Convolutional Neural Network (CNN) implemented in TensorFlow/Keras
- **Goal**: Binary classification — Parkinsonian tremor vs. normal movement

---

## 🛠️ Technologies Used

- `TensorFlow` / `Keras` – for deep learning model
- `OpenCV` – for image preprocessing
- `NumPy`, `Pandas`, `Matplotlib` – for data handling and visualization
- `Jupyter Notebook` – development environment
- mmWave radar data (converted into 2D Doppler images)

---

## 🔍 Model Pipeline

1. **Preprocessing**
   - Convert raw radar signals into 2D Doppler images
   - Normalize and resize input data

2. **Model Architecture**
   - CNN with Conv2D → MaxPooling → Dropout layers
   - Binary classification with sigmoid output

3. **Training**
   - Loss: Binary Crossentropy  
   - Optimizer: Adam  
   - Evaluation metrics: Accuracy, Precision, Recall

4. **Inference**
   - Predict Parkinson’s likelihood on unseen radar image samples

---

## 📊 Results

- Accuracy: ~94% on test set  
- Model shows strong ability to distinguish Parkinson tremor patterns based on radar image features.
---

## 🤝 Acknowledgements

- Texas Instruments mmWave SDK  
- OpenCV community for image processing insights  
- Academic datasets for Parkinson-related tremor references

---

## 📬 Contact

**Emircan Demirel**  
[GitHub](https://github.com/emircand) • [LinkedIn](https://linkedin.com/in/emircand) • emircandemirel@yahoo.com
