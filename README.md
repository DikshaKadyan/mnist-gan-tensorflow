# MNIST GAN using TensorFlow

This project demonstrates how to generate **handwritten digits** from the **MNIST dataset** using a **Generative Adversarial Network (GAN)** implemented in **TensorFlow**.

---

## 📌 Project Overview
- Dataset: **MNIST** (handwritten digits 0–9)
- Model: **GAN (Generative Adversarial Network)**
  - **Generator**: Creates synthetic handwritten digits.
  - **Discriminator**: Classifies images as real (from MNIST) or fake (from Generator).
- Training process improves the Generator until it produces realistic-looking digits.

---

## 🚀 Features
- Load and preprocess MNIST dataset
- Build and train GAN with TensorFlow/Keras
- Generate new handwritten digit images
- Save & visualize generated outputs

---

## 🛠️ Tech Stack
- **Python 3**
- **TensorFlow / Keras**
- NumPy, Matplotlib
- Google Colab (for training & experimentation)

---

## 📂 Files
- `mnist_gan.ipynb` → Main Colab notebook with GAN implementation  
- `README.md` → Project documentation  

---

## ▶️ How to Run
1. Open the notebook in **Google Colab**:  
   [Click Here to Open in Colab]([https://colab.research.google.com/drive/1j7Q3ruDDSyooSyE3ZI0Z4LKZg7qVFaJs?usp=sharing](https://colab.research.google.com/drive/1W8JM8EARuu8ADrWVVNYOe0d8_E9zKl9t?usp=sharing))  

2. Run cells step by step:
   - Load MNIST dataset  
   - Build Generator & Discriminator models  
   - Train the GAN  
   - Generate and visualize digits

---

## 🙌 Acknowledgements
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)  
- TensorFlow & Keras Documentation  
- Ian Goodfellow et al. (GANs Paper, 2014)
