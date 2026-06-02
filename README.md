# 🧠 Brain Tumor Classification Using Transfer Learning

## 📌 Project Overview

This project focuses on the multiclass classification of brain tumors from MRI images using state-of-the-art Transfer Learning models. The objective is to evaluate and compare the performance of multiple pre-trained Convolutional Neural Networks (CNNs) in accurately identifying different categories of brain tumors.

The models evaluated in this study include:

- VGG16
- VGG19
- ResNet50
- InceptionV3
- Xception

A comprehensive performance comparison was conducted using classification metrics, confusion matrices, and visual performance analysis to identify the most effective architecture for brain tumor classification.

---

## 🎯 Objectives

- Perform brain tumor classification using Transfer Learning.
- Compare the performance of multiple deep learning architectures.
- Evaluate model effectiveness using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- Visualize and compare model performance through graphs and plots.
- Identify the best-performing architecture for the given dataset.

---

## 📂 Dataset

The dataset consists of MRI brain scan images categorized into different tumor classes.

### Classes

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

### Dataset Statistics

| Description | Value |
|------------|--------|
| Total Images | 16,600 |
| Number of Classes | 4 |
| Image Type | MRI Scans |
| Task | Multiclass Classification |

---

## 🏗️ Project Workflow

```text
MRI Images
     │
     ▼
Data Preprocessing
     │
     ▼
Train-Test Split
     │
     ▼
Transfer Learning Models
(VGG16, VGG19, ResNet50, InceptionV3, Xception)
     │
     ▼
Model Training
     │
     ▼
Prediction
     │
     ▼
Performance Evaluation
     │
     ├── Accuracy
     ├── Precision
     ├── Recall
     ├── F1-Score
     └── Confusion Matrix
     │
     ▼
Model Comparison & Analysis
```

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Kaggle Notebook Environment

---

## 🤖 Transfer Learning Models

### 1. VGG16
Pre-trained CNN architecture with 16 weight layers known for its simplicity and strong feature extraction capabilities.

### 2. VGG19
An enhanced version of VGG16 with deeper architecture and improved feature learning capacity.

### 3. ResNet50
Residual Network containing skip connections that help overcome the vanishing gradient problem.

### 4. InceptionV3
Computationally efficient architecture that utilizes inception modules to capture multi-scale features.

### 5. Xception
An advanced architecture based on depthwise separable convolutions, providing high accuracy with efficient computation.

---

# 📈 Accuracy Comparison

<img width="790" height="490" alt="accuracy" src="https://github.com/user-attachments/assets/5c26f4f6-2d10-4a34-b4ad-f70ef72b2c6f" />

---

# 📈 Precision, Recall & F1-Score Comparision

## Glioma

<img width="987" height="590" alt="glioma" src="https://github.com/user-attachments/assets/235ae500-3c51-4034-a349-2cf2f3676778" />

---

## Meningioma

<img width="987" height="590" alt="meningioma" src="https://github.com/user-attachments/assets/93752ec1-c296-41f1-8ce9-80097443bc3f" />

---

## Pituitary

<img width="987" height="590" alt="pituitary" src="https://github.com/user-attachments/assets/8a991681-d032-412a-af93-0ae062081b32" />

---

## No Tumor

<img width="987" height="590" alt="notumor" src="https://github.com/user-attachments/assets/e9ea9af8-24cd-43a0-9619-1d09dfb6c2ff" />

---

# 🔍 Confusion Matrices

## VGG16

<img width="648" height="491" alt="vgg-16" src="https://github.com/user-attachments/assets/29a3141b-0efa-4b8b-a8a6-e03c669b898c" />

---

## VGG19

<img width="647" height="492" alt="vgg-19" src="https://github.com/user-attachments/assets/42c3ad5b-145f-4501-ab3a-59132db14cf4" />

---

## ResNet50

<img width="646" height="490" alt="resnet50" src="https://github.com/user-attachments/assets/fa88649f-78f1-458a-8ba7-a16c73aa106e" />

---

## InceptionV3

<img width="649" height="490" alt="inception" src="https://github.com/user-attachments/assets/23fb1c02-677d-4248-990a-fc5f1e80a873" />

---

## Xception

<img width="647" height="486" alt="xception" src="https://github.com/user-attachments/assets/d26e1b1e-5fa6-48b2-be11-ad8d48c8b20d" />

---

# 🏆 Results and Findings

### Key Observations

- Transfer learning significantly improved classification performance.
- All models demonstrated strong feature extraction capability for MRI images.
- Performance varied across architectures due to differences in network depth and feature learning mechanisms.
- Confusion matrix analysis highlighted class-wise strengths and weaknesses.
- The best-performing model achieved the highest balance between precision, recall, and F1-score.

### Best Model

| Metric | Value |
|----------|--------|
| Model | Xception |
| Validation Accuracy | 96.99% |
| Precision | 97.00% |
| Recall | 96.75% |
| F1-Score | 97.00% |

---

# 📚 References

1. TensorFlow Documentation
2. Keras Applications
3. Scikit-Learn Documentation
4. Brain MRI Dataset Source
5. Research papers on Transfer Learning for Medical Image Classification

---

# 👨‍💻 Author

**Ashish Pandey**

- Data Engineering & AI Enthusiast
- Interested in Machine Learning, Deep Learning, Data Engineering, and Cloud Technologies

---

## ⭐ If you found this project useful, consider giving it a star!
