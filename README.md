# 📧 EMAIL-SPAM-DETECTION

A simple and effective spam email detection project using a neural network built with TensorFlow and Scikit-learn. This model classifies messages as **Spam** or **Ham** with high accuracy, using the SMS Spam Collection Dataset.

---

## 🚀 Features

- Text preprocessing using CountVectorizer
- Deep learning model using TensorFlow Keras
- High accuracy (✅ Final Test Accuracy: **99.01%**)
- Evaluation using confusion matrix and classification report
- Test predictions on custom messages
- Developed and tested in Google Colab

---

## 📁 Dataset

- **Name**: [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- **Source**: UCI Machine Learning Repository
- **Columns**:
  - `Category`: Spam or Ham
  - `Message`: The actual message content
- ✅ Dataset already uploaded in this repository

---

## 🧠 Model Architecture

- **Input**: CountVectorized text
- **Layers**:
  - `Dense(64, activation='relu')`
  - `Dense(32, activation='relu')`
  - `Dense(1, activation='sigmoid')`
- **Loss**: Binary Crossentropy
- **Optimizer**: Adam

---

## 📊 Performance

- ✅ **Final Test Accuracy**: **99.01%**

### 🧾 Classification Report:

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| Ham   | 0.99      | 1.00   | 1.00     |
| Spam  | 1.00      | 0.97   | 0.98     |
| **Avg/Total** | **0.99** | **0.99** | **0.99** |

### 🧮 Confusion Matrix:

| Actual \ Predicted | Ham | Spam |
|--------------------|-----|------|
| **Ham**            | 965 |  0   |
| **Spam**           |  10 | 139  |

---





