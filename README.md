# 🌱 Plant Disease Detection

A machine learning and deep learning project for detecting plant diseases using the **PlantVillage dataset**.

The project explores three different approaches:

- **Artificial Neural Network (ANN)**
- **Convolutional Neural Network (CNN)**
- **Support Vector Machine (SVM)**

## 📌 Project Overview

Plant diseases can significantly affect crop production and agricultural productivity. This project uses machine learning and deep learning techniques to classify plant leaf images and identify different plant diseases.

The models are trained using the **PlantVillage dataset** and their performance is evaluated using validation accuracy and other evaluation metrics.

## 🤖 Models Used

### 1. Artificial Neural Network (ANN)

An ANN model was trained for plant disease classification using the processed PlantVillage dataset.

### 2. Convolutional Neural Network (CNN)

CNN was used to learn visual features directly from plant leaf images and classify them into different disease categories.

### 3. Support Vector Machine (SVM)

SVM was used as a traditional machine learning approach for plant disease classification.

## 📊 Results

The project includes trained models and their evaluation results.

### CNN

- Final validation accuracy: **93.37%**
- Best validation accuracy during training: **94.31%**

The trained CNN model is saved as:

`plant_disease_model.h5`

## 📂 Project Structure

```text
plant-disease-detection/
│
├── model/
│   └── Trained model files
│
├── notebooks/
│   ├── ANN_Plant_Disease_Model.ipynb
│   ├── Plant_Disease_Detection.ipynb
│   └── README.md
│
├── results/
│   └── Model results and evaluation files
│
├── README.md
├── requirements.txt
└── .gitattributes
🗃️ Dataset
The project uses the PlantVillage dataset, which contains images of plant leaves belonging to different plant disease categories.
🛠️ Technologies Used
Python
TensorFlow
Keras
Scikit-learn
NumPy
Pandas
Matplotlib
Google Colab
Jupyter Notebook
⚙️ Models and Technologies
Model
Type
ANN
Deep Learning
CNN
Deep Learning
SVM
Machine Learning
🚀 Project Workflow
PlantVillage Dataset
        ↓
Data Preprocessing
        ↓
Feature/Image Processing
        ↓
Model Training
        ↓
ANN / CNN / SVM
        ↓
Model Evaluation
        ↓
Disease Classification
🎯 Objective
The main objective of this project is to explore and compare different machine learning and deep learning approaches for plant disease detection.
🔮 Future Scope
Improve model accuracy
Add more plant disease categories
Deploy the trained model as a web application
Develop a user-friendly interface for uploading leaf images
Explore real-time plant disease detection
👩‍💻 Author
Vanshika Sharma
Plant Disease Detection Project
BCA Academic Project
