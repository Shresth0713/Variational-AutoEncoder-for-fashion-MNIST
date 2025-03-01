# Variational-AutoEncoder-for-fashion-MNIST
This project implements a Variational Autoencoder (VAE) trained on the Fashion MNIST dataset using TensorFlow and Keras. Unlike a traditional autoencoder, a VAE learns a probabilistic latent space, which allows it to generate new, realistic-looking images by sampling from this learned distribution.


# 🧠 Variational Autoencoder (VAE) for Fashion MNIST

This repository contains a **Variational Autoencoder (VAE)** trained on the **Fashion MNIST dataset** using TensorFlow and Keras. A VAE is a generative model that learns a **probabilistic latent space** representation of input data and can generate new samples.

## 🚀 Features
- **Variational Autoencoder (VAE) architecture**
- **Probabilistic encoding & reparameterization trick**
- **Comparison of Original vs Reconstructed Images**
- **Latent Space Visualization (if `latent_dim=2`)**
- **New Image Generation by sampling the latent space**
- **Pretrained model for easy use (`vae_model.h5`)**

## 📂 Dataset
Fashion MNIST consists of **70,000 grayscale images** (28x28 pixels) in **10 clothing categories**:
- 👕 T-shirt/top
- 👖 Trouser
- 🧥 Pullover
- 👗 Dress
- 🧥 Coat
- 👡 Sandal
- 👕 Shirt
- 👟 Sneaker
- 👜 Bag
- 👢 Ankle boot
