# asl-translator
Translating Sign Language words using Computer Vision Model
# ASL Image Translator – Real-Time Letter & Number Detection

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/ASL_Translator.ipynb)

This project is a real-time American Sign Language (ASL) Translator that detects hand-signed **letters (A–Z)**, **numbers (0–9)**, and **common phrases** from uploaded images. Built entirely in **Google Colab**, it offers an automated pipeline that includes:

- Dataset loading (via Roboflow or Kaggle)
- Data preprocessing and splitting
- CNN model training and evaluation
- Live prediction from uploaded images
- Accuracy reports and confusion matrix visualization

---

## Features include:

-  **No manual file handling** – All datasets are loaded directly from the cloud.
-  **End-to-end deep learning** – Convolutional Neural Network (CNN) built using TensorFlow/Keras.
-  **Live prediction** – Upload a test image to see real-time ASL classification.
-  **Detailed evaluation** – Accuracy metrics, classification report, and confusion matrix included.
-  **One-click launch** – Runs seamlessly in Colab (see badge above).

---

## Dataset:

This notebook uses the **ASL Alphabet Dataset** from Kaggle:

[Kaggle Dataset - ASL Alphabet by grassknoted](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

> You can choose either Kaggle or Roboflow integration (preconfigured in the notebook).

---

## Installation (if not using Colab)

Clone the repo and install dependencies locally:
```bash
git clone https://github.com/Alibek-07/asl-translator.git
cd asl-translator
pip install -r requirements.txt

