# 🧠 Alzheimer’s Disease Detection using CNN

## 📌 Overview

This project focuses on detecting and classifying stages of Alzheimer’s disease from brain MRI images using **Convolutional Neural Networks (CNN)**. The model analyzes MRI scans and classifies them into four categories, helping in early diagnosis and medical decision support.

---

## 🎯 Problem Statement

Alzheimer’s disease is a progressive neurological disorder that affects memory and cognitive abilities. Early detection is crucial but often requires expert analysis of MRI scans. This project aims to automate the classification process using deep learning techniques.

---

## 🧩 Features

* Multi-class classification of MRI images
* Detects 4 stages of Alzheimer’s:

  * Mild Impairment
  * Moderate Impairment
  * Very Mild Impairment
  * No Impairment
* Image preprocessing using OpenCV
* CNN-based deep learning model
* Performance evaluation using accuracy, confusion matrix, and classification report

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn

---

## 📂 Dataset

The dataset consists of MRI images categorized into four classes.

### 📁 Structure:

Dataset/
├── train/
│   ├── Mild Impairment
│   ├── Moderate Impairment
│   ├── Very Mild Impairment
│   └── No Impairment
│
└── test/
├── Mild Impairment
├── Moderate Impairment
├── Very Mild Impairment
└── No Impairment

> ⚠️ Note: Dataset is not included in this repository due to size. You can download it from Kaggle.
> 
link - https://www.kaggle.com/datasets/lukechugh/best-alzheimer-mri-dataset-99-accuracy
---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Alzheimer-Detection-CNN.git
cd Alzheimer-Detection-CNN
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Project

```bash
python train.py
```

---

## 🚀 How It Works

1. Upload and extract dataset
2. Preprocess images (resize, normalize)
3. Load training and testing data
4. Train CNN model
5. Evaluate performance
6. Generate predictions

---

## 📊 Results

* Model Accuracy: ~85–95%
* Training vs Validation accuracy plotted
* Confusion Matrix generated
* Classification Report with Precision, Recall, F1-score

---

## 📸 Output Samples

(Add your screenshots here)

* Accuracy Graph
* Confusion Matrix
* Sample Predictions

---

## ⚠️ Challenges Faced

* Dataset imbalance
* Overfitting
* Limited computational resources
* Variability in MRI images

---

## 🔮 Future Improvements

* Use Transfer Learning (ResNet, VGG16)
* Improve accuracy with data augmentation
* Deploy as a web application
* Real-time prediction system

---

## 📁 Project Structure

```
Alzheimer-Detection-CNN/
│
├── dataset/
├── notebooks/
├── src/
├── models/
├── outputs/
├── README.md
├── requirements.txt
└── report.pdf
```
##Course
Computer Vision(CSE3010)- Bring your own Project(BYOP) Capstone
Faculty:Rakesh Srivastava | Slot:B21+E14
---

## 👨‍💻 Author

**Md Shadaan Ashraf**
Reg No: 23BAI10399
B.Tech CSE (AIML)
VIT Bhopal University

---
