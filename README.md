# 🧠 Brain Tumor Detection using Convolutional Neural Networks (CNN)

A deep learning project for classifying brain MRI images into four categories using a Convolutional Neural Network (CNN) built with TensorFlow and Keras.

> **Current Version:** V1 (Baseline CNN)

---

## 📌 Project Overview

Early detection of brain tumors is critical for effective diagnosis and treatment. This project aims to classify brain MRI images into different tumor categories using a CNN developed from scratch.

This repository currently contains the baseline version of the model. Future versions will focus on improving generalization using advanced CNN architectures and transfer learning.

---

## 🎯 Objective

Build an end-to-end deep learning pipeline for brain tumor classification that includes:

- Data preprocessing
- CNN model development
- Model training
- Model evaluation
- Model versioning

---

## 🗂 Dataset

**Dataset:** Brain Tumor Classification MRI Dataset

**Classes:**

- Glioma Tumor
- Meningioma Tumor
- No Tumor
- Pituitary Tumor

The dataset is organized into:

```
Train/
Validation/
Test/
```

Images are resized to **224 × 224** pixels before training.

---

## 🛠 Tech Stack

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
brain-tumor-detection/

│
├── data/
│
├── models/
│   └── brain_tumor_cnn_v1.keras
│
├── notebooks/
│   ├── 01-data-understanding.ipynb
│   ├── 02-data-preprocessing.ipynb
│   └── 03-model-training.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Image resizing (224 × 224)
- TensorFlow Dataset creation
- Batch generation
- Data shuffling (training only)

---

## 🧠 CNN Architecture (Version 1)

The baseline model consists of:

- Rescaling Layer
- Convolution Layers
- MaxPooling Layers
- Flatten Layer
- Dense Layers
- Softmax Output Layer

---

## 📈 Training

The model was trained using:

- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam
- Evaluation Metric: Accuracy

---

## 📊 Results (Version 1)

| Metric | Value |
|---------|------:|
| Validation Accuracy | ~84% |
| Test Accuracy | 52.28% |
| Test Loss | 3.7786 |

The first version serves as a baseline implementation for future improvements.

---

## 🚀 Future Improvements

Planned enhancements include:

- Improved CNN architecture
- Data augmentation
- Hyperparameter tuning
- Transfer Learning
  - MobileNetV2
  - EfficientNetB0
- FastAPI inference API
- Model deployment
- Improved documentation

---

## 📌 Model Version

Current model:

```
brain_tumor_cnn_v1.keras
```

---



## 👨‍💻 Author

**Ashutosh Kashyap**

BS-MS in Artificial Intelligence & Cyber Security  
Indian Institute of Technology Patna

---

⭐ This repository represents **Version 1 (Baseline)** of the Brain Tumor Detection project. Future versions will focus on improving model performance, robustness, and deployment.