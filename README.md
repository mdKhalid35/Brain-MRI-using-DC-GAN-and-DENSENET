# Brain-MRI-using-DC-GAN-and-DENSENET

# Synthetic Brain MRI Generation using DC-GAN & DenseNet 🧠

![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-AI-blue?style=for-the-badge)

## 📌 Project Overview
Machine learning in healthcare is frequently bottlenecked by the scarcity of high-quality, diverse medical imaging data due to patient privacy constraints. This project directly addresses this issue by utilizing Generative AI to create highly realistic, synthetic brain MRI scans. 

By integrating a **Deep Convolutional Generative Adversarial Network (DC-GAN)** with a **DenseNet** architecture, this system generates high-resolution medical images that can be used to safely train downstream classification pipelines without compromising patient data.

> **Note:** The novel architecture and methodologies developed in this project have been approved for patent filing by the university Intellectual Property (IP) Cell.

## 🏗️ Architecture & Technical Innovations
Traditional GANs often struggle with **mode collapse** (generating the same image repeatedly) and training instability. To solve this, I engineered a custom pipeline:

* **Dense Feature Propagation:** Integrated DenseNet concepts into the generator to maximize information flow between layers, resulting in sharper, more anatomically accurate brain structures.
* **Adversarial Optimization:** Meticulously tuned the adversarial loss and learning rates between the generator and discriminator to ensure stable convergence and prevent the discriminator from overpowering the generator in early epochs.
* **Framework:** Built entirely from scratch using **Python** and **PyTorch**.

## 🛠️ Tech Stack
* **Core Machine Learning:** PyTorch, 
* **Data Processing:** NumPy, Pandas
* **Visualization:** Matplotlib, OpenCV
* **Environment:**  Google Colab

## 📊 Results & Output




![Sample 1](path/to/your/image1.png) | ![Sample 2](path/to/your/image2.png) 
:-------------------------:|:-------------------------:
*Epoch 10: Early Formation* | *Epoch 60: High-Resolution Synthetic MRI*



### Prerequisites
Ensure you have Python 3.8+ installed. Install the required dependencies:
```bash
pip install torch torchvision numpy matplotlib opencv-python
