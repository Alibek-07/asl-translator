# Asl-Translator
Translating Sign Language words using Computer Vision Model
# ASL Image Translator – Real-Time Letter & Number Detection

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/ASL_Translator.ipynb)

This project is a deep learning-powered **ASL (American Sign Language) Translator** that enables real-time and batch image classification of ASL gestures. It is built using **YOLOv8** for object detection and classification, and runs entirely in **Google Colab**, eliminating the need for manual file handling.

- Dataset loading (via Roboflow or Kaggle)
- Data preprocessing and splitting
- CNN model training and evaluation
- Live prediction from uploaded images
- Accuracy reports and confusion matrix visualization

---

## Features include:

-  **No manual file handling** – All datasets are loaded directly from the cloud.
-  **End-to-end deep learning** – Convolutional Neural Network (CNN) built using TensorFlow/Keras.
-  **Model** - Trained YOLOv8 on ASL letter dataset via Roboflow
-  **Live prediction** – Upload a test image to see real-time ASL classification.
-  **Detailed evaluation** -  Automatic generation of:
  - Confusion Matrix
  - Classification Report
  - Accuracy & Loss Plots
-  **One-click launch** – Runs fully on Google Colab – no local setup needed

---

- This project uses a **deep convolutional neural network (CNN)** architecture via **YOLOv8**, which is a real-time object detection model. The model has multiple convolutional layers and was trained on ASL data, making this a strong example of an applied **deep learning** solution.

- Visualizations & Metrics
- Accuracy & Loss Graphs (auto-generated during training)
- Confusion Matrix
- Per-Class Precision, Recall, and F1-Score Table
> **Note**: If they don’t render on GitHub, open the Colab notebook to regenerate and view interactively.

## Dataset:

This notebook uses the **ASL Alphabet Dataset** from Kaggle:

[Kaggle Dataset - ASL Alphabet by grassknoted](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

> You can choose either Kaggle or Roboflow integration (preconfigured in the notebook).

---

## Installation (if not using Colab)
- You don’t need local installation. Just open the Colab notebook and run:

Clone the repo and install dependencies locally:
```bash
git clone https://github.com/Alibek-07/asl-translator.git
cd asl-translator
pip install -r requirements.txt

## Author

**Alibek Dadajonov**  
GitHub: [Alibek-07](https://github.com/Alibek-07)

---

## License

This project is open-source under the MIT License.

