# 🖋️ Signature Forgery Detection using Siamese Neural Network

This project implements a **Siamese Neural Network (SNN)** to verify handwritten signatures and detect forgeries. By learning to measure the similarity between signature image pairs, the model is trained to distinguish between **genuine** and **forged** signatures, even with limited samples.

---

## 🔍 What is a Siamese Neural Network?

A **Siamese Neural Network** is a unique architecture consisting of two identical neural networks (with shared weights) that process two input images in parallel. It outputs a similarity score or distance metric indicating how alike the two signatures are.

---

## 🧠 Features

- ✅ Siamese Neural Network with shared convolutional layers
- 🔍 Contrastive loss function for training
- 📸 Image pair preprocessing
- 📊 Model evaluation using accuracy and distance thresholds
- 📈 Visualizations of training metrics and prediction results

---

## 🛠️ Tech Stack

- Python 3.x
- Jupyter Notebook
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib / Seaborn
- OpenCV / PIL for image preprocessing

---

## 📂 Dataset Format

Supports datasets like the [CEDAR Signature Dataset](http://www.iapr-tc11.org/mediawiki/index.php/CEDAR_Forgery_Database) or custom datasets with this structure:

