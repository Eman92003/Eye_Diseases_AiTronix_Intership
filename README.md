# **AiTronix Internship Project**

This repository contains a Jupyter Notebook developed during the **AiTronix AI Internship**.  
The project focuses on building and comparing multiple deep learning models for **eye disease image classification**.

---

## 📌 Project Summary

Three different deep learning models were implemented and evaluated to classify eye diseases from medical images.  
Each model was trained, validated, and compared based on performance metrics to identify the most effective architecture.

### 🔍 Models & Performance

| Model | Description | Accuracy |
|------|------------|----------|
| Model 1 | Custom CNN Model | **87%** |
| Model 2 | Transfer Learning (VGG16) | **90%** |
| Model 3 | Transfer Learning (VGG16 unfreezed) | **91%** |

**Note:** Accuracy values are obtained from the validation set and are documented inside the notebook.

---

## 📁 Dataset

- **Source:** Kaggle ([link]((https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification)))  
- **Size:** ~4000 images  
- **Classes:** 4 eye disease categories (cataract,diabetic_retinopathy,glaucoma,normal)  
- **Data Augmentation:** Applied **light augmentation only**.
Care was taken to **avoid aggressive transformations** due to the medical nature of the images.

---

## 🧠 Methodology

The workflow implemented in the notebook includes:

- Image loading and preprocessing  
- Light data augmentation  
- Training multiple CNN architectures  
- Model evaluation and comparison  

---

## 📊 Model Evaluation

Evaluation techniques include:

- **Accuracy & Loss Curves**  
- **Classification Report** (Precision, Recall, F1-Score)  
- **Confusion Matrix**  

These metrics provide detailed insight into each model’s performance beyond overall accuracy.

---

## 🛠 Tools & Technologies Used

- **Python**  
- **Jupyter Notebook**  
- **TensorFlow / Keras**  
- **NumPy & Matplotlib**  
- **scikit-learn** (`classification_report`, `confusion_matrix`)  

---
