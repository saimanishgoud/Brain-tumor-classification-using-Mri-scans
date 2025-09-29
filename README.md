
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

> Dataset Source: [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/datasets) (or replace with your dataset link).

---

## 🛠️ Tech Stack

* **Language:** Python 3.9+
* **Framework:** PyTorch
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, Torchvision, Scikit-learn, OpenCV

---

## ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/your-username/brain-tumor-classification.git
cd brain-tumor-classification
```

Create a virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🧑‍💻 Usage

1. Place the dataset in the `data/` folder.
2. Run training:

```bash
python train.py
```

3. Run testing:

```bash
python test.py
```

4. Visualize results (graphs, heatmaps):

```bash
python visualize.py
```

---

## 📊 Results

* Achieved **92% accuracy** on the test dataset.
* Generated Grad-CAM heatmaps highlighting tumor regions.
* Example prediction:

| Input MRI                            | Predicted Class | Heatmap                               |
| ------------------------------------ | --------------- | ------------------------------------- |
| ![Sample MRI]() | Glioma          | ![Heatmap](<img width="700" height="600" alt="heatmaps" src="https://github.com/user-attachments/assets/0737942a-8fbb-476a-bcfd-2c953992e64e" />
) |

---

## 🏥 Applications

* Assisting radiologists in medical diagnosis.
* Research on automated tumor classification.
* Can be extended to other

