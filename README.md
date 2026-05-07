# 🛡️ Hate Speech Detection using CNN

This project applies a **Convolutional Neural Network (CNN)** to detect hate speech in text data. It leverages deep learning to classify text as *hateful*, *offensive*, or *neutral*, helping improve content moderation and online safety.

---

## ✨ Features

- 🔤 Text preprocessing: tokenization, padding, and encoding
- 🧠 CNN-based model for sentence-level classification
- 📈 Training and evaluation with performance metrics
- 📊 Visualization of training results
- 💬 Real-time predictions from user input

---

## 🧰 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **NumPy & Pandas**
- **Matplotlib & Seaborn**

---

## 🎯 Project Motivation

This project was developed to explore how deep learning and natural language processing can be used to identify harmful online content. The goal was to understand how AI models can contribute to safer digital communication platforms.

---

## 📚 Dataset Information

The model was trained on a labeled text dataset containing hateful, offensive, and neutral speech categories. Text preprocessing techniques such as tokenization, padding, and encoding were applied before training.

---

## 🧠 Model Architecture

- Embedding Layer
- Convolutional Neural Network (CNN)
- Pooling Layer
- Dense Output Layer

The model was trained using TensorFlow/Keras.

---

## 📈 Results

The model was successfully trained to classify text into different categories. Training and validation accuracy/loss graphs were generated to evaluate model performance during training.

---

## ⚙️ Getting Started

### 📥 Installation

1. Clone the repository:

```bash
git clone https://github.com/krishnaM-byte/hate-speech-detection-cnn.git
cd hate-speech-detection-cnn
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

### Train the model

```bash
python train.py
```

### Test or predict

```bash
python predict.py
```

---

## 🚀 Future Improvements

- Improve dataset quality and size
- Experiment with advanced NLP models
- Deploy the model as a web application
- Improve classification accuracy

---

## 📌 Future Scope

This project can be extended into a real-time moderation tool for social media platforms, online communities, and educational environments to help reduce harmful digital interactions.
