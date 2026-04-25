# 🧠 COVID-19 Detection using Chest X-Ray Images

## 📌 Overview

This project implements a deep learning model to detect COVID-19 infection from chest X-ray images. The system classifies images into categories such as COVID-19, Normal, and Viral Pneumonia.

---

## ❗ Problem Statement

To build an automated system that can accurately detect COVID-19 from chest X-ray images using deep learning techniques.

---

## 📊 Dataset

* Source: Kaggle COVID-19 Radiography Database
* Dataset Link: https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

**Includes:**

* COVID-19 cases
* Normal cases
* Viral Pneumonia cases

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Image resizing and normalization
* Label encoding
* Train-test split

### 2. Model

* Convolutional Neural Network (CNN)

**Layers include:**

* Convolution layers
* MaxPooling
* Dense layers
* Activation functions (ReLU, Softmax)

### 3. Training

* Loss Function: Categorical Crossentropy
* Optimizer: Adam
* Evaluation metrics: Accuracy

---

## 📈 Results

* Model Accuracy: **89%**
* Achieved on validation dataset
* The model shows good performance in distinguishing COVID-19 cases

### 📊 Model Performance

![Accuracy](images/accuracy.png)

---

## 🚀 How to Run

```bash
git clone https://github.com/AishwaryGhadle/covid19-xray-detection.git
cd covid19-xray-detection
pip install -r requirements.txt
jupyter notebook
```

Open:

```bash
COVID-19 detection.ipynb
```

---

## 📁 Project Structure

```
covid19-xray-detection/
│
├── COVID-19 detection.ipynb
├── report.docx
├── README.md
├── requirements.txt
├── images/
    └── accuracy.png
```

---

## 📌 Future Improvements

* Use transfer learning (ResNet, VGG16)
* Improve dataset balance
* Deploy as web application

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

**Aishwary Ghadle**


---

## 👤 Author

**Aishwary Ghadle**

