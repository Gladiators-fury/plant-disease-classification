# 🌿 Plant Disease Classification using Transfer Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

## 📌 Project Overview

Plant diseases significantly affect agricultural productivity and crop quality worldwide. Early and accurate disease identification enables farmers to take timely preventive measures and reduce crop losses.

This project develops an **automated Plant Disease Classification System** using **Transfer Learning** and **Convolutional Neural Networks (CNNs)**. The model classifies plant leaf images into **38 disease categories** using the **PlantVillage** dataset.

The project compares multiple pretrained deep learning architectures to determine the most effective model for plant disease recognition.

---

## 🎯 Objectives

- Develop a robust plant disease classification model.
- Compare multiple Transfer Learning architectures.
- Improve classification accuracy using fine-tuning.
- Handle class imbalance using class weights.
- Build a foundation for future real-world deployment.

---

## 📂 Dataset

**Dataset:** PlantVillage

- Total Images: **54,305**
- Training Images: **43,444**
- Validation Images: **10,861**
- Classes: **38**
- Image Size: **224 × 224**

The dataset contains healthy and diseased leaves from multiple crop species.

---

## 🧠 Deep Learning Models

This project evaluates multiple pretrained CNN architectures.

| Model | Status |
|--------|--------|
| ✅ ResNet50 | Completed |
| 🚧 DenseNet121 | In Progress |
| 🚧 EfficientNetB0 | In Progress |

---

## ⚙️ Transfer Learning Strategy

### Stage 1

- ImageNet pretrained weights
- Frozen convolutional backbone
- Train custom classifier

### Stage 2

- Unfreeze last 50 layers
- Fine-tune using learning rate = 1e-5
- EarlyStopping
- ReduceLROnPlateau
- ModelCheckpoint

---

# 📈 Results

## ResNet50

| Metric | Value |
|---------|-------:|
| Training Accuracy | **97.65%** |
| Validation Accuracy | **98.74%** |
| Validation Loss | **0.0370** |

The fine-tuned ResNet50 model achieved excellent classification performance on the PlantVillage dataset while maintaining strong generalization capability.

---

# 📊 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

# 🖼️ Results

## Accuracy Curve

> *(Add accuracy graph here)*

---

## Loss Curve

> *(Add loss graph here)*

---

## Confusion Matrix

> *(Add confusion matrix here)*

---

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenCV

---

# 📁 Repository Structure

```text
plant-disease-classification/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── images/
├── models/
└── reports/
```

---

# 🚀 Future Improvements

- Complete DenseNet121 implementation
- Complete EfficientNetB0 implementation
- Grad-CAM visualization
- Web application deployment
- Mobile application deployment
- Real-world field image testing

---

# 📚 References

- PlantVillage Dataset
- TensorFlow Documentation
- Keras Applications
- ResNet50 Research Paper

---

# 👨‍💻 Author

**Deb Kamal Ghosh**

B.Tech Computer Science & Engineering

Machine Learning & Deep Learning Enthusiast

---

⭐ If you found this project useful, consider giving it a star!
