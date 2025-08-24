# 🖼️ MNIST Digit Classification

This repository contains an implementation of the **MNIST Handwritten Digit Classification** project.  
The MNIST dataset is one of the most popular datasets in the field of Machine Learning and Deep Learning, consisting of **70,000 grayscale images** of handwritten digits (0–9), each of size **28x28 pixels**.

---

## 📂 Project Structure

MNIST/
├── data/ # Dataset files (mnist_train.csv, mnist_test.csv)
├── notebooks/ # Jupyter notebooks for experiments
├── models/ # Saved models
├── src/ # Source code (training, evaluation, utils)
├── requirements.txt # Required Python packages
└── README.md # Project documentation

---

## 🚀 Features
- Preprocessing and visualization of MNIST dataset.
- Training models using:
  - Logistic Regression
  - Random Forest
  - Neural Networks (MLP, CNN)
- Evaluation of model performance with accuracy, confusion matrix, and classification reports.
- Model saving and reloading for predictions.

---

## 🔧 Installation

1. Clone this repository:
   git clone https://github.com/Aditibhoir/MNIST.git
   cd MNIST
   
2.(Optional) Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3.Install required dependencies:

pip install -r requirements.txt

🖥️ Usage
**Train the model**
python src/train.py

**Evaluate the model**
python src/evaluate.py

**Run Jupyter Notebook**
jupyter notebook notebooks/MNIST_Classification.ipynb

📈 Results

Logistic Regression Accuracy: ~92%

Random Forest Accuracy: ~96%

CNN Model Accuracy: ~99%
