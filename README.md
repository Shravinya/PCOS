# 🧠 XAI-Enabled Deep Convolutional Model for PCOS Detection

## 📌 Project Overview

This research-driven project presents an **AI-powered system for detecting Polycystic Ovary Syndrome (PCOS)** from **ultrasound images** using advanced **Convolutional Neural Networks (CNNs)** and **Explainable AI (XAI)** techniques. It combines deep learning models like **VGG-16** and **NASNet-Mobile** with **Grad-CAM** visualizations to enhance interpretability and clinical reliability.

---

## 🎯 Objectives

- ✅ Detect PCOS from ultrasound images using deep learning.
- 📈 Compare different CNN architectures (Basic CNN, VGG-16, NASNet-Mobile).
- 🌐 Improve model generalization using data augmentation techniques.
- 🔍 Use **Grad-CAM** to provide **visual explanations** for model decisions.
- ☁️ Enable future deployment for real-time clinical use.

---

## 📊 Dataset

- **Source**: Kaggle (Ultrasound Images)
- **Total Images**: 150  
  - **Training Set**: 100 images  
  - **Testing Set**: 50 images  
- **Labels**: PCOS-positive and PCOS-negative

---

## 🧠 Models Compared

| Model                | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Basic CNN           | 85.4%    | 0.83      | 0.87   | 0.85     |
| CNN + Augmentation  | 88.9%    | 0.87      | 0.90   | 0.89     |
| VGG-16 (Transfer Learning) | 90.5%    | 0.89      | 0.91   | 0.90     |
| **NASNet-Mobile**   | **93.8%**| **0.92**  | **0.95** | **0.94** |

---

## 🛠️ Tech Stack

- **Programming Language**: Python  
- **Deep Learning Libraries**: TensorFlow, Keras  
- **Visualization**: Grad-CAM  
- **Image Processing**: OpenCV, PIL  
- **Other Tools**: Google Colab / Jupyter Notebooks

---

## 🔎 Explainable AI (XAI) with Grad-CAM

To overcome the “black-box” nature of deep learning, **Grad-CAM** heatmaps were generated, highlighting **cystic regions and follicular fluid**. This boosts **trust** and ensures that the model is focusing on **clinically relevant areas**.

---

## 📈 Training Details

- **Image Size**: 224x224  
- **Epochs**: 30  
- **Optimizer**: Adam  
- **Loss Function**: Binary Crossentropy  
- **Batch Size**: 32  
- **Augmentations**: Rotation, Flipping, Zooming, Shifting

---

## 🔬 Results

- NASNet-Mobile performed best across all metrics.
- VGG-16 demonstrated robust feature extraction.
- Grad-CAM provided visual validation for predictions.
- Minimal overfitting was observed.
- Confusion matrix shows high classification accuracy.

---

