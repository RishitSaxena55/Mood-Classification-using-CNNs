# Mood Classification using CNNs

This project demonstrates a deep learning pipeline using Convolutional Neural Networks (CNNs) to classify human moods based on facial expression images.

---

## 🧠 Objective

To train a CNN model that predicts mood/emotion categories such as happy, sad, angry, etc., from facial images.

---

## 📊 Dataset

The dataset contains preprocessed facial images (typically 48x48 grayscale) labeled with emotion classes like:

- Happy
- Sad
- Angry
- Neutral
- Surprised

---

## 🏗️ Model Architecture

- Input: 48x48 grayscale images
- Multiple Conv2D layers with ReLU activation
- MaxPooling layers to reduce spatial size
- Dropout for regularization
- Flatten → Dense layers
- Output: Softmax layer for classification

---

## 🧪 Evaluation

- Accuracy and loss graphs for training/validation
- Confusion matrix to analyze performance
- Test set evaluation metrics

---

## 🛠️ Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/RishitSaxena55/mood-classifier-cnn.git
   cd mood-classifier-cnn
