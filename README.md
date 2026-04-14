# 🧠 Convolutional Neural Networks (CNN) Lab Assignment

## 📌 Overview

This project implements a complete pipeline for understanding and building **Convolutional Neural Networks (CNNs)** using **TensorFlow/Keras**. It covers everything from data preprocessing to advanced topics like interpretability and transfer learning.

---

## 🚀 Objectives

* Build CNNs from scratch
* Understand training, tuning, and regularisation
* Visualise learned features and model behavior
* Apply transfer learning on real-world datasets

---

## 📂 Dataset

* **MNIST** → Handwritten digits (grayscale, 28×28)
* **CIFAR-10** → 10 object classes (RGB, 32×32)

---

## 🧩 Project Structure

```
📁 CNN-Lab
│── Task1_DataPipeline.ipynb
│── Task2_CNN_From_Scratch.ipynb
│── Task3_Training_Tuning.ipynb
│── Task4_Visualization.ipynb
│── Task5_TransferLearning.ipynb
│── merged_notebook.ipynb
│── README.md
│── outputs/
│    ├── dataset_samples.png
│    ├── augmentation_demo.png
│    ├── lenet_sgd_curves.png
│    ├── optimiser_comparison.png
│    ├── confusion_matrix.png
│    ├── gradcam_results.png
│    └── tl_benchmark.png
```

---

## ⚙️ Tech Stack

* Python 🐍
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn

---

## 🏗️ Tasks Implemented

### 🔹 Task 1: Data Pipeline

* Dataset loading and exploration
* Preprocessing (normalisation, reshaping, one-hot encoding)
* Data augmentation

### 🔹 Task 2: CNN from Scratch

* Manual convolution using NumPy
* Implementation of **LeNet-5**
* Custom CNN architecture for CIFAR-10

### 🔹 Task 3: Training & Regularisation

* Optimiser comparison (SGD, Adam)
* Learning rate & batch size tuning
* Regularisation (Dropout, BatchNorm)
* Learning rate scheduling

### 🔹 Task 4: Visualisation & Interpretability

* Filter visualisation
* Feature maps extraction
* Grad-CAM heatmaps
* Confusion matrix & classification report

### 🔹 Task 5: Transfer Learning

* Pretrained models (VGG16 / ResNet50)
* Fine-tuning strategies
* Performance benchmarking

---

## 📊 Key Features

* Reproducibility (random seed = 42)
* Clean modular code
* Visual outputs for all experiments
* Comparative analysis across models

---

## 📈 Results

* Achieved high accuracy on MNIST and CIFAR-10
* Demonstrated impact of:

  * Learning rate
  * Batch size
  * Regularisation techniques
* Transfer learning significantly improved performance

---

## ▶️ How to Run

```bash
# Install dependencies
pip install tensorflow numpy matplotlib seaborn scikit-learn

# Run notebook
jupyter notebook
```

---

## 📌 Notes

* All models built from scratch (no external code)
* Plots saved as PNG as required
* Notebook is fully executable and reproducible

---

## 👤 Author

* Muskan
* Machine Learning Enthusiast 🚀

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub!
