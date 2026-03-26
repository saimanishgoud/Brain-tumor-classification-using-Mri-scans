
# 🧠 Brain Tumor Classification from MRI Scans

This project focuses on building a **Deep Learning model** to classify brain tumors from MRI images into four categories:

* **Glioma**
* **Meningioma**
* **Pituitary Tumor**
* **No Tumor**

The goal is to assist medical professionals in faster and more accurate tumor detection using **Convolutional Neural Networks (CNNs)** implemented in **PyTorch**.

---

## 🚀 Features

* Preprocessing of MRI scans (resizing, normalization, augmentation).
* CNN-based deep learning model built using PyTorch.
* Training and validation pipelines with accuracy and loss graphs.
* **Model evaluation metrics:** Accuracy, Precision, Recall, F1-score.
* **Heatmaps (Grad-CAM)** for model interpretability.
* Graphical representation of predictions.

---

## 📂 Dataset

The dataset consists of labeled MRI scans divided into four categories:

* **Training set**
* **Test set**

> Dataset Source: [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset))

---

## 🛠️ Tech Stack

* **Language:** Python 3.9+
* **Framework:** PyTorch
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Torchvision, Scikit-learn, OpenCV




## 📊 Results

* Achieved **92% test accuracy** across 4 tumor classes on 7,000+ MRI scans
* Applied data augmentation to handle class imbalance
* Generated Grad-CAM heatmaps highlighting tumor regions.




## 🏥 Applications

* Assisting radiologists in medical diagnosis.
* Research on automated tumor classification.


