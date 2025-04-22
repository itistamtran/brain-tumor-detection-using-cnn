# 🧠 Brain Tumor Detection using CNN

This project uses a Convolutional Neural Network (CNN) to classify brain MRI images as **tumor** or **no tumor**. The model was trained and evaluated using a public MRI dataset and achieved high accuracy and F1 score on unseen test data.

---

## 📁 Dataset

- **Source**: [Brain Tumor MRI Dataset on Kaggle](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)
- The dataset includes four categories: `glioma`, `meningioma`, `pituitary`, and `notumor`

---

## 🛠️ Model & Training

- Model: Custom CNN built using Keras Functional API
- Input size: 240x240 RGB images
- Training techniques:
  - EarlyStopping
  - ModelCheckpoint (best model saved)
- Final metrics:
  - **Test Accuracy**: 98%
  - **F1 Score**: 0.98

---

## 🧪 Results

### 🔹 Classification Report (on test set)

## 👨‍🏫 Advisor: Dr. Hao Ji
**Semester:** Spring 2025  
**Institution:** Cal Poly Pomona

🙏 **Acknowledgments**

Project adapted from [Mohamed Ali Habib's Brain Tumor Detection Notebook](https://github.com/MohamedAliHabib/Brain-Tumor-Detection/blob/master/Brain%20Tumor%20Detection.ipynb)

Dataset provided by Masoud Nickparvar on Kaggle
