# 🧠 COVID-19 Detection using Chest X-Ray Images

## 📌 Overview

This project implements a deep learning model to detect COVID-19 infection from chest X-ray images.

---

## ❗ Problem Statement

To detect whether a patient is COVID-19 positive using X-ray images and deep learning.

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

### Data Preprocessing

* Image resizing and normalization
* Label encoding
* Train-test split

### Model

* Convolutional Neural Network (CNN)

### Training

* Loss Function: Categorical Crossentropy
* Optimizer: Adam
* Metric: Accuracy

---

## 📈 Results

* Model Accuracy: **89%**
* Achieved on validation dataset

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
covid19_detection.ipynb
```

---

## 📁 Project Structure

```bash
covid19-xray-detection/
│
├── covid19_detection.ipynb
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

MIT License

---

## 👤 Author

**Aishwary Ghadle**


