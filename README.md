# Structural-Health-Monitoring

# Crack Detection Using Deep Learning (Image Segmentation)

This project implements a **deep learning–based image segmentation model** to detect cracks in images.  
It uses **TensorFlow and Keras** to train a convolutional neural network on labeled crack images and corresponding binary masks.

---

## 📘 Project Overview

Crack detection is an important problem in structural health monitoring and civil engineering.  
This notebook builds an **end-to-end image segmentation pipeline** that:

- Loads crack images and ground-truth masks
- Preprocesses and resizes data
- Trains a neural network to segment cracks
- Evaluates the model using standard classification metrics

---

## 🛠️ Technologies & Libraries Used

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📂 Dataset Structure
The project assumes the following directory structure

QuakeCity/
│
├── image/
│ ├── crack/ # Images containing cracks
│ └── no_crack/ # Images without cracks
│
└── label/
└── crack/ # Binary mask images (ground truth)

## ⚙️ Configuration Parameters

Key parameters used in the notebook:

- Image size: `256 × 256`
- Batch size: `8`
- Random seed: `42`
- Binary segmentation masks

---

## 🔄 Data Processing Pipeline

- Images and masks are loaded using TensorFlow I/O
- Images are resized and normalized
- Masks are thresholded to binary format
- Dataset is split into:
  - Training set
  - Validation set
  - Test set

---

## 🧠 Model Details

- Convolutional Neural Network for **image segmentation**
- Binary classification at pixel level
- Trained using TensorFlow/Keras
- Evaluation includes:
  - Confusion Matrix
  - Precision, Recall, F1-Score
 
## Sample output
<img width="1176" height="786" alt="image" src="https://github.com/user-attachments/assets/3075b240-ac9f-46f2-80b7-d07cf1aca6a9" />



