# 🧠 Brain Tumor Detection using Deep Learning (VGG16)

This project implements a **Brain Tumor Detection system** using **Transfer Learning with VGG16** to classify MRI brain images into **No Tumor** and **Pituitary Tumor** categories. The model achieves **high accuracy** by leveraging pre-trained convolutional neural networks and effective data augmentation techniques.

---

## 📌 Project Overview

Brain tumor detection from MRI scans is a critical task in medical diagnosis. This project automates the detection process using deep learning, reducing manual effort and improving diagnostic accuracy.

**Key Highlights:**
- Binary classification of MRI images
- Transfer Learning using pre-trained VGG16
- Extensive data augmentation
- High accuracy on unseen test data

---

## 🗂️ Dataset

The dataset consists of MRI brain images organized into two classes:

- **No Tumor**
- **Pituitary Tumor**

### Data Augmentation Techniques:
- Image resizing to `224 × 224`
- Horizontal flipping
- 90° rotation
- Mirrored rotation

Augmentation increases dataset diversity and improves model generalization.

---

## 🛠️ Technologies Used

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Scikit-learn**

---

## 🧠 Model Architecture

- **Base Model:** VGG16 (pre-trained on ImageNet)
- **Frozen Layers:** Convolutional base
- **Custom Classification Head:**
  - Global Average Pooling
  - Dense Layers (1024 → 1024 → 512)
  - Softmax Output (2 classes)

**Loss Function:** Categorical Crossentropy  
**Optimizer:** Adam  

---

## 📈 Model Performance

| Metric | Value |
|------|------|
| Training Accuracy | ~99% |
| Validation Accuracy | ~99.8% |
| Epochs | 5 |

The model converges quickly due to transfer learning and achieves excellent generalization.

