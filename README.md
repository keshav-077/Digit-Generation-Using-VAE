# 🧠 Digit Generation using Variational Autoencoder (VAE)

This project demonstrates how to build and train a **Variational Autoencoder (VAE)** using TensorFlow/Keras to generate new handwritten digits similar to those in the **MNIST dataset**.  

A VAE is a type of generative model that learns compressed latent representations of input data and can generate new samples by sampling from this latent space.

---

## 📌 Project Overview
- **Dataset**: [MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/)  
- **Model**: Variational Autoencoder (Encoder + Decoder + Sampling Layer)  
- **Latent Dimension**: 2 (for visualization of the latent space)  
- **Frameworks**: TensorFlow, Keras, NumPy, Matplotlib  

---

## 🚀 Features
- Preprocessing and normalization of MNIST digits.  
- Custom **Sampling Layer** for the reparameterization trick.  
- Convolutional **Encoder** and **Decoder** architectures.  
- Combined **Reconstruction Loss + KL Divergence Loss** for training.  
- Visualization of latent space and generated digits.  

---

## 🛠️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/Digit_Generation_VAE.git
cd Digit_Generation_VAE
pip install -r requirements.txt


## 📂 Project Structure
Digit_Generation_VAE/
│── Digit_Generation_VAE.ipynb   # Main Jupyter Notebook
│── requirements.txt             # Project dependencies
│── README.md                    # Project documentation

📊 Results

The trained VAE learns a smooth latent space where nearby points generate similar digits.

By sampling from the latent space, the model generates new handwritten digits.

Example of generated digits:

📝 Future Improvements

Train with higher latent dimensions for richer representations.

Apply to more complex datasets (e.g., Fashion-MNIST, CIFAR-10).

Extend the model with Conditional VAEs (CVAE).
