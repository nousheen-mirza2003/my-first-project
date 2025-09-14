# Lung Cancer Detection using Deep Learning

This project implements an **ensemble 2D CNN (Convolutional Neural Network)** approach for detecting lung cancer from medical images.  
It was developed as part of my engineering project to explore deep learning applications in healthcare.

---

##  Project Overview
- The goal is to assist doctors by providing an automated system to detect possible lung cancer cases from CT scan images.
- Uses **deep learning models** to analyze medical image datasets.
- Ensemble approach: combines multiple CNN architectures to improve accuracy.

---

## 🛠 Tools & Technologies
- **Python**
- **TensorFlow / Keras**
- **NumPy, Pandas, Matplotlib**
- **Jupyter Notebook** for experiments

---

## Dataset
- Publicly available lung CT scan datasets were used.
- Preprocessing steps included image resizing, normalization, and data augmentation.

---

##  How It Works
1. Preprocesses CT scan images into uniform sizes.  
2. Trains multiple CNN models on the dataset.  
3. Combines predictions using ensemble learning for improved performance.  
4. Outputs prediction: *Normal* or *Cancer Detected*.

---

##  Results
- Achieved good accuracy on validation data.  
- Ensemble models outperformed individual CNNs.  

---

##  Future Enhancements
- Train on larger medical datasets.  
- Deploy as a **web app** for easy usage by doctors.  
- Improve explainability using **Grad-CAM** (heatmaps).  

---

##  Author
**NOUSHEEN MIRZA**  
B.E (2025), Sri Siddhartha School of Engineering  
