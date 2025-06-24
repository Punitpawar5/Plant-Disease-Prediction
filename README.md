# 🌿 Plant Disease Detection Using Deep Learning

## 🔖 Overview

This project implements a Convolutional Neural Network (CNN) to classify plant leaf diseases from images using the PlantVillage dataset. The model helps detect plant diseases early, improving diagnosis and supporting sustainable agriculture.

---

## 🔍 Problem Statement

Manual disease detection in crops is error-prone, slow, and requires expert knowledge. This project automates the identification of plant leaf diseases using image classification, enabling fast and accurate detection without expert intervention.

---

## 📂 Dataset

* **Source**: [Kaggle - PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
* **Images**: Colored images of healthy and diseased leaves
* **Classes**: 38+ categories (e.g., Apple Scab, Tomato Mosaic Virus, Healthy)
* **Format**: JPG images grouped by class in folders
* **Split**: 80% training, 20% validation using `ImageDataGenerator`

---

## 🔧 Technologies Used

* Python
* TensorFlow / Keras
* NumPy, Matplotlib
* Google Colab (for training)

---

## 🔧 Model Architecture

* **Input Layer**: Resized 256x256 RGB images
* **Convolutional Layers**: Feature extraction
* **MaxPooling**: Dimensionality reduction
* **Dropout**: To reduce overfitting
* **Dense Layers**: Fully connected neural layers
* **Output**: Softmax activation for multi-class classification

---

## 📊 Results (Sample)

| Metric              | Value                  |
| ------------------- | ---------------------- |
| Training Accuracy   | \~78%                  |
| Validation Accuracy | \~85%                  |
| Loss                | Decreasing             |
| Prediction Example  | `Tomato___Target_Spot` |

---

## 🌍 Future Work

* Use Transfer Learning (e.g., MobileNet, ResNet)
* Deploy using Streamlit or Gradio
* Build a mobile app for farmers
* Integrate weather data for predictive analytics

---

## 📖 License

This project is licensed under the MIT License.

---

## 🌟 Credits

* [Kaggle - PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
* Inspired by real-world agricultural challenges.
