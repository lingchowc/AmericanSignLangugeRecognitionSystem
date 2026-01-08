# Real-Time American Sign Language (ASL) Recognition
**Computer Vision & Natural Language Processing**

This repository contains a Jupyter Notebook implementation of a real-time American Sign Language (ASL) recognition system.  
The project applies **Computer Vision** techniques for hand gesture processing and **Natural Language Processing** concepts to convert recognized gestures into textual output.

---

## Dataset

This project uses the **American Sign Language (ASL) dataset** from Kaggle:
  https://www.kaggle.com/code/alpayabbaszade/american-sign-language/notebook

The dataset contains labeled images of static ASL hand gestures representing alphabet characters, which are used to train and evaluate the classification model.

---

## What This Notebook Covers

### 1. Data Preparation
- Loading ASL image data from the Kaggle dataset
- Image preprocessing and normalization
- Label encoding for gesture classification

### 2. Computer Vision
- Image-based hand gesture processing
- Feature extraction for model input
- Webcam input handling using OpenCV

### 3. Model Development
- Deep learning model construction using TensorFlow / Keras
- Model training and validation on ASL image data
- Performance evaluation and visualization

### 4. Real-Time Recognition
- Live webcam-based gesture prediction
- Continuous frame-by-frame inference
- Real-time display of predicted ASL characters

### 5. Natural Language Processing
- Mapping predicted gesture classes to textual representations
- Character-level language output

---

## Tech Stack Used

- **Programming Language:** Python  
- **Computer Vision:** OpenCV  
- **Deep Learning:** TensorFlow, Keras  
- **Numerical Computing:** NumPy  
- **Data Handling:** Pandas  
- **Visualization:** Matplotlib  
- **Development Environment:** Jupyter Notebook  

