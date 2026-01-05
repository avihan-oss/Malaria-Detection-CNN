# Malaria Parasite Detection using CNN 🦟🔬

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-TensorFlow-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview
Malaria is a life-threatening disease caused by parasites that are transmitted to people through the bites of infected female Anopheles mosquitoes. Manual diagnosis requires a pathologist to examine blood smears under a microscope, which is time-consuming and prone to error.

This project automates the detection process using **Deep Learning**. I built a **Convolutional Neural Network (CNN)** to classify microscopic images of erythrocytes (red blood cells) as either:
* **Parasitized:** Containing the Plasmodium parasite.
* **Uninfected:** Healthy cells.

## 🧠 Model Architecture
The model is a custom sequential CNN built with **TensorFlow/Keras**:
* **Input Layer:** Resized 64x64 RGB images.
* **Feature Extraction:** 3 Convolutional Blocks (Conv2D + ReLU + MaxPooling).
* **Classification Head:** Flatten -> Dense (64 units) -> Output (Sigmoid for binary classification).

## 🚀 Key Results
* **Dataset:** Official NIH Malaria Dataset (via `tensorflow_datasets`).
* **Training Accuracy:** ~95% after 5 epochs.
* **Impact:** Demonstrates the potential of AI to assist in rapid medical diagnosis in resource-constrained regions.

## 🛠️ Tech Stack
* **Framework:** TensorFlow, Keras
* **Data Processing:** NumPy, TensorFlow Datasets
* **Visualization:** Matplotlib

## 💻 How to Run
Click the **"Open in Colab"** badge above to run the notebook in your browser.
