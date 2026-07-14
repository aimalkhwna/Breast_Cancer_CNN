
## 📌 Project Overview

This project implements an Artificial Neural Network (ANN) using TensorFlow/Keras to classify breast tumors as **Benign** or **Malignant** based on diagnostic measurements.

The workflow includes data preprocessing, feature scaling, model training, evaluation, and prediction using a Deep Learning model.

---

## 🎯 Objectives

- Perform binary classification using an ANN.
- Preprocess and normalize medical data.
- Train and evaluate a neural network.
- Prevent overfitting using Early Stopping.
- Save the trained model for future predictions.

---

## 📂 Dataset

The project uses the **Breast Cancer Wisconsin Diagnostic Dataset**.

### Features

The dataset contains **30 numerical features**, including:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

### Target

- **0 → Malignant**
- **1 → Benign**

---

## 🧠 Model Architecture

```text
Input Layer (30 Features)
        │
        ▼
Dense Layer (20 neurons, ReLU)
        │
        ▼
Output Layer (1 neuron, Sigmoid)
```

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Joblib

---

## 📊 Workflow

1. Load Dataset
2. Data Preprocessing
3. Train-Test Split
4. Feature Scaling
5. Build ANN Model
6. Model Training
7. Early Stopping
8. Model Evaluation
9. Prediction
10. Save Model

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Breast-Cancer-Prediction.git
```

Move into the project folder

```bash
cd Breast-Cancer-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📷 Project Screenshots

Add screenshots here.

Example:

```
images/
├── accuracy.png
├── loss.png
├── confusion_matrix.png
```

---

## 📁 Project Structure

```
Breast-Cancer-Prediction
│
├── Breast_Cancer.ipynb
├── README.md
├── requirements.txt
├── Breast_Cancer.keras
├── images/
└── dataset/
```

---

## 💡 Future Improvements

- Hyperparameter tuning
- Cross Validation
- Model Deployment using FastAPI
- Docker Containerization
- Streamlit Web Application

---

## 👨‍💻 Author

**Aimal Khan**

Computer Science Student

Interested in:

- Machine Learning
- Deep Learning
- Computer Vision
- Artificial Intelligence

---

## ⭐ If you found this project useful, consider giving it a Star.
