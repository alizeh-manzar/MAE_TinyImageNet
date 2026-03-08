# Masked Autoencoder (MAE) for TinyImageNet

## Project Overview
This project implements a **self-supervised Masked Autoencoder (MAE)** using **PyTorch** to learn meaningful visual representations by reconstructing masked patches. The model is trained on the **TinyImageNet** dataset and demonstrates **image reconstruction, quantitative evaluation (PSNR & SSIM), and interactive visualization**.

---

## Features
- **Encoder (ViT-Base):** Processes only **25% visible patches** from input images.  
- **Decoder (ViT-Small):** Reconstructs **75% masked patches**.  
- **Self-supervised Learning:** Learns without labels by predicting masked content.  
- **Evaluation:**  
  - **PSNR** (Peak Signal-to-Noise Ratio)  
  - **SSIM** (Structural Similarity Index Measure)  
- **Visualization:** Compare **masked input**, **reconstruction**, and **original images**.  
- **Interactive Gradio App:** Upload custom images and see real-time reconstruction.

---


