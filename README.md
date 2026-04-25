# 🧠 COVID-19 Detection using Chest X-Ray Images

## 📌 Overview

This project implements a deep learning model to detect COVID-19 infection from chest X-ray images. The system classifies images into categories such as COVID-19, Normal, and Viral Pneumonia.

---

## ❗ Problem Statement

To build an automated system that can accurately detect COVID-19 from chest X-ray images using deep learning techniques.

---

## 📊 Dataset

## 📊 Dataset

* Source: Kaggle COVID-19 Radiography Database  
* Dataset Link: https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database  

* Includes:

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
* Layers include:

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

- Model Accuracy: **89%**
- Achieved on the validation dataset
- The model shows good performance in distinguishing COVID-19 cases from normal and pneumonia classes.


---

## 🚀 How to Run

1. Clone repository:

```bash
git clone https://github.com/AishwaryGhadle/covid19-xray-detection.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

4. Open:

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

