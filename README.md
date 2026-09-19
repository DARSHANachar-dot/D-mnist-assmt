# 🧠 MNIST Handwritten Digit Classification

## 📌 About the Project

This project is a Deep Learning model for recognizing handwritten digits from **0 to 9** using the **MNIST dataset**.

The model is built using **TensorFlow and Keras**.

## 📊 Dataset

- 60,000 training images
- 10,000 testing images
- 10 digit classes (0–9)
- Image size: 28 × 28 pixels

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## 🧠 Model Architecture

The neural network contains:

- Flatten layer
- Dense layer with 128 neurons and ReLU activation
- Output layer with 10 neurons and Softmax activation

## ⚙️ Training

- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 5
- Validation Split: 10%

## 📈 Results

The model achieved:

**Test Accuracy: 97.49%**

### Sample Predictions

| Actual | Predicted |
|--------|-----------|
| 7 | 7 |
| 2 | 2 |
| 1 | 1 |
| 0 | 0 |
| 4
