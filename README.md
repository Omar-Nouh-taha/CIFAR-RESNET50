# CIFAR-10 Object Detection using ResNet50

## 📌 Project Overview

This project focuses on building an image classification system using the **CIFAR-10 dataset** and a deep learning model based on **ResNet50**. The goal is to classify images into one of 10 categories such as airplanes, cars, birds, cats, and more.

The project demonstrates a complete pipeline starting from data loading and preprocessing to model training and evaluation.

---

## 📂 Dataset

The dataset used is **CIFAR-10**, which contains:

* 60,000 color images
* Image size: **32 × 32 × 3**
* 10 classes:

  * Airplane
  * Automobile
  * Bird
  * Cat
  * Deer
  * Dog
  * Frog
  * Horse
  * Ship
  * Truck

Dataset split:

* Training: 50,000 images
* Testing: 10,000 images

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

---

## 🔄 Workflow

### 1. Data Loading

* Loaded dataset from `.npy` files or directly using TensorFlow.
* Verified dataset shape and structure.

### 2. Data Preprocessing

* Normalized pixel values (0–255 → 0–1)
* Converted labels from text to numeric using mapping
* Handled missing or inconsistent labels
* Split dataset into training and testing sets

### 3. Data Visualization

* Displayed sample images using OpenCV and Matplotlib
* Verified correct label-image mapping

### 4. Model Building

* Used **ResNet50** as the base model
* Adjusted input layer to match CIFAR-10 size
* Added custom classification layers

### 5. Training

* Trained model on training data
* Used validation split to monitor performance
* Tuned hyperparameters

### 6. Evaluation

* Evaluated model on test data
* Measured accuracy and loss
* Analyzed predictions

---


## 📊 Results

* Successfully trained a classification model on CIFAR-10
* Achieved reasonable accuracy for a baseline deep learning model
* Built a reusable pipeline for image classification tasks

---

## ⭐ Conclusion

This project provides a solid foundation for understanding image classification using deep learning and highlights common pitfalls in handling real-world datasets.
