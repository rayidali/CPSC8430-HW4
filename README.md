# CPSC8430-HW4
# Generative Adversarial Networks (GANs) for Image Generation

This repository contains the implementation and comparison of three Generative Adversarial Network (GAN) architectures: Deep Convolutional GAN (DCGAN), Wasserstein GAN (WGAN), and Auxiliary Classifier GAN (ACGAN) for generating high-quality images.

## Introduction
Generative Adversarial Networks (GANs) are a powerful class of deep learning models that can generate realistic images by learning the underlying distribution of the training data. In this project, we explore and compare three popular GAN architectures: DCGAN, WGAN, and ACGAN.

- **DCGAN**: Deep Convolutional GAN, which uses convolutional layers in the generator and discriminator networks.
- **WGAN**: Wasserstein GAN, which modifies the loss function to improve training stability and image quality.
- **ACGAN**: Auxiliary Classifier GAN, which incorporates an auxiliary classifier in the discriminator to generate class-conditioned images.

## Installation
To run the code in this repository, you need to have the following dependencies installed:
- Python (version X.X.X)
- PyTorch (version X.X.X)
- torchvision (version X.X.X)
- NumPy (version X.X.X)
- Matplotlib (version X.X.X)

## Usage
To train and evaluate the GAN models, follow these steps:
1. Clone the repository
2. Navigate to the project directory
3. Run the desired GAN model
