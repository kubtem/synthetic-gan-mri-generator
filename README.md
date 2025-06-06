# Synthetic GAN MRI Generator
🧬☢️💉🩺🧪🔬🧫🩻🧑‍⚕️🏥⚛️

A generative adversarial network (GAN) for synthesizing brain MRI images, trained on real brain MRI scans. This project is designed to explore synthetic data generation techniques in medical imaging.

## 🧠 Overview

This project trains a Deep Convolutional GAN (DCGAN) model using grayscale MRI brain scans. It aims to generate synthetic MRI-like images that resemble the structure and texture of real MRIs, with potential use in data augmentation for deep learning tasks.

## 📂 Dataset

- **Source**: [Brain MRI Images for Brain Tumor Detection (Kaggle)](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
- Images are grayscale and resized to 128x128 pixels.

## ⚙️ Model Architecture

- **Generator**: Sequential Conv2DTranspose layers to upscale noise vectors to image size.
- **Discriminator**: Conv2D layers to classify real vs fake images.
- Optimized using Binary Cross Entropy and Adam optimizers.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/synthetic-gan-mri-generator.git
   cd synthetic-gan-mri-generator
2. Make sure you have Python 3.8+, TensorFlow, NumPy, OpenCV installed.

3. Place the dataset inside a folder named brain_mri_dataset/ (or change the path in the script).

4. Run the notebook or script to train the GAN.

## 🖼️ Output
The model generates synthetic MRI images after each epoch.
Sample output:


## 📌 Notes

This project is for research and educational purposes.

Data is anonymized and public; no patient information is included.
