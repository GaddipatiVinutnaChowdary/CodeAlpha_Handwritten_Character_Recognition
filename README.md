# ✍️ Handwritten Character Recognition using CNN

> **CodeAlpha Machine Learning Internship – Task 3**

## 📌 Project Overview

This project implements a **Handwritten Character Recognition System** using a **Convolutional Neural Network (CNN)** and the **MNIST dataset**. The model is trained to recognize handwritten digits (0–9) from grayscale images and demonstrates the complete deep learning workflow, from preprocessing to prediction.

---

## 🎯 Objective

Develop a deep learning model that accurately recognizes handwritten digits using image processing and a Convolutional Neural Network (CNN).

---

## 📂 Dataset

**Dataset:** MNIST Handwritten Digits

- Training Images: **60,000**
- Testing Images: **10,000**
- Image Size: **28 × 28 pixels**
- Classes: **10 (Digits 0–9)**

The dataset is loaded directly using TensorFlow:

```python
from tensorflow.keras.datasets import mnist
```

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 CNN Architecture

- Conv2D (32 Filters)
- MaxPooling2D
- Conv2D (64 Filters)
- MaxPooling2D
- Flatten
- Dense (128 Neurons)
- Dropout
- Output Layer (Softmax)

---

## 🚀 Project Workflow

- Import Required Libraries
- Load MNIST Dataset
- Display Sample Images
- Normalize Images
- Reshape Input Data
- One-Hot Encode Labels
- Build CNN Model
- Compile Model
- Train Model
- Evaluate Performance
- Plot Accuracy & Loss Graphs
- Generate Confusion Matrix
- Display Classification Report
- Predict Handwritten Digits
- Save Trained Model

---

# 📷 Project Results

## Sample Handwritten Digits

![Sample Digits](images/sample_digits.png)

---

## Training & Validation Accuracy

![Accuracy Graph](images/accuracy.png)

---

## Training & Validation Loss

![Loss Graph](images/loss.png)

---

## Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## Prediction Example

![Prediction](images/prediction.png)

---

## 📊 Model Evaluation

The model performance is evaluated using:

- Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss
- Confusion Matrix
- Classification Report

---

## 💾 Model Output

The trained model is saved as:

```
handwritten_character_model.keras
```

---

## 📁 Repository Structure

```
CodeAlpha_Handwritten_Character_Recognition/
│
├── CodeAlpha_Handwritten_Character_Recognition.ipynb
├── handwritten_character_model.keras
├── README.md
├── requirements.txt
└── images/
    ├── sample_digits.png
    ├── accuracy.png
    ├── loss.png
    ├── confusion_matrix.png
    └── prediction.png
```

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**.
2. Run all cells from top to bottom.
3. The MNIST dataset will download automatically.
4. Train the CNN model.
5. Evaluate the model.
6. Test predictions on handwritten digits.

---

## 📌 Conclusion

This project successfully demonstrates handwritten digit recognition using **Convolutional Neural Networks (CNNs)**. The model learns meaningful image features from the MNIST dataset and accurately classifies handwritten digits, making it a strong example of image classification using deep learning.

---

## 👨‍💻 Internship

**CodeAlpha – Machine Learning Internship**

**Task 3: Handwritten Character Recognition**

---

⭐ **If you found this project useful, please consider giving this repository a star
