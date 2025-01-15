# LSTM Autoencoder for Reconstructing Blurred Images

This project explores the application of a **Long Short-Term Memory (LSTM)** based autoencoder for reconstructing blurred images from the **CIFAR-10 dataset**. It focuses on improving image quality through tasks like image compression, noise reduction, and reconstruction.

## Overview

Autoencoders are widely used for image quality enhancement, and this study evaluates the effectiveness of an LSTM autoencoder in recovering image features. The **CIFAR-10 dataset**, containing 60,000 32x32 pixel images from 10 classes, was used as the benchmark. Gaussian blur was applied to simulate real-world image degradation, and the autoencoder was trained to reconstruct clear images from the blurred inputs.

### Key Features:
- **Dataset:** CIFAR-10 (10 classes, 32x32 pixel resolution).
- **Preprocessing:** Gaussian blur applied to simulate degraded image quality.
- **Model:** LSTM autoencoder trained to reconstruct high-quality images.
- **Evaluation:** Mean Squared Error (MSE) loss for measuring reconstruction quality.

## Highlights of Results

- The **LSTM autoencoder** effectively captured spatial and temporal dependencies in the image data.
- Produced **high-quality reconstructions** with minimal error, as indicated by small final MSE values.
- Demonstrated the potential of LSTM-based architectures for image denoising and feature recovery.

## Future Directions

This study highlights the promise of LSTM autoencoders for image reconstruction. Potential improvements include:
- **Variational Autoencoders (VAEs):** To incorporate probabilistic modeling for sharper reconstructions.
- **Generative Adversarial Networks (GANs):** To enhance reconstruction sharpness further.

## Usage

### Requirements
- Python 3.x
- TensorFlow / PyTorch
- CIFAR-10 dataset
- Additional libraries: NumPy, Matplotlib, etc.

### Steps to Reproduce
1. Clone this repository:
   ```bash
   git clone https://github.com/MuhammadAyob/Application-of-Long-Short-Term-Memory-LSTM-Autoencoder-for-Image-Reconstruction.git
   cd Application-of-Long-Short-Term-Memory-LSTM-Autoencoder-for-Image-Reconstruction

## Conclusion

This project demonstrates the capability of LSTM autoencoders in reconstructing blurred images and lays the groundwork for further exploration with advanced architectures. This repository is for demonstration purposes only. Code usage or distribution is not permitted without permission.

## NB. Usage

This repository is intended for **demonstration purposes only**. The code is not licensed for public use, reproduction, or distribution without explicit permission from the author.

