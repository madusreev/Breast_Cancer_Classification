# Breast Cancer Classification using CNN (CancerNet)

This repository contains a Jupyter Notebook for classifying IDC breast cancer histology images as benign or malignant using a CNN model. The notebook includes data preprocessing, model training, evaluation, and visualization of results.

# Breast Cancer Classification (CancerNet)

**Objective:** Build a CNN model (CancerNet) to classify IDC histology images as benign or malignant.

**Dataset:** IDC_regular dataset from Kaggle (50×50 image patches, total 2,77,524 samples).  

**Project Steps:**
1. **Data Preparation:** Load and preprocess images (resize, normalization).  
2. **Model Architecture:** CNN with Conv2D, MaxPooling, Dropout, and Dense layers.  
3. **Training:** 10 epochs, batch size 32, optimizer: Adam.  
4. **Evaluation:** Accuracy, confusion matrix, classification report.  
5. **Visualization:** Plots for accuracy and loss trends.  

**Results:**  
- Accuracy: ~91.5%  
- Confusion matrix highlights benign vs malignant classification performance.  

**Usage:**  
1. Clone the repository:  
   ```bash
   git clone <repository-url>




# Breast Cancer Classification using CNN (CancerNet)

## Objective
To build a breast cancer classifier on an IDC dataset that can accurately classify a histology image as **benign** or **malignant**.

## Problem Statement
Imagine yourself as a Chief Data Scientist working in a big medical company in partnership with cancer hospitals. The mission is to **identify cancerous patients early**, before terminal illness, enabling early treatment and saving lives. Breast cancer (BC) is one of the most common cancers among women worldwide, representing the majority of new cancer cases and cancer-related deaths.  

Early diagnosis improves prognosis and chances of survival, while accurate classification of benign tumors prevents unnecessary treatments. Your role is to collect biological microscopic images and build an AI algorithm that can detect **benign or malignant cancers** with high accuracy and precision.

## Business Goal
Develop a classifier using a **Convolutional Neural Network (CNN)** to analyze breast cancer histology images. The model, named **CancerNet**, is trained on the IDC dataset using Keras, aiming for high classification accuracy.  

## Project Steps

1. **Data Preparation**  
   Collect and prepare the IDC histology image dataset, organizing and preprocessing the images for training.

2. **Model Architecture (CancerNet)**  
   Design the CNN architecture using Keras, including layers, filters, pooling, and activation functions to capture image features effectively.

3. **Training**  
   Train the model using backpropagation, adjusting weights iteratively to improve accuracy.

4. **Model Evaluation**  
   Assess performance using metrics like **accuracy, precision, recall, and F1-score**.

5. **Confusion Matrix**  
   Analyze true positive, true negative, false positive, and false negative predictions.

6. **Performance Analysis**  
   Evaluate model strengths and weaknesses in detecting cancerous vs non-cancerous images.

7. **Outcome**  
   A trained **CancerNet** model capable of classifying breast cancer histology images with high accuracy, useful for medical practitioners and research.

## Dataset
**Invasive Ductal Carcinoma (IDC)** is the most common breast cancer subtype.  

- Dataset: IDC_regular (Kaggle)  
- Patches: 277,524 of size 50×50 from 162 whole mount slide images  
- Negative: 198,738 | Positive: 78,786 (IDC)  
- Scanned at 40x magnification  
- Requires minimum 3.02GB disk space  

## Questions & Analysis

- **Training & Testing Split:** 80:20  
- **Epochs / Iterations:** 10  
- **Algorithm Choice:** CNN is effective for image datasets; other options could include **ResNet, VGG, EfficientNet** for better feature extraction.  
- **Accuracy:**  
  - After 5 epochs: ~91.5%  
  - After 10 epochs: ~91.5%  
- **Model Assessment:** Slight overfitting possible; training and validation accuracy similar. Optimizations possible with more data augmentation or fine-tuning.  
- **Real-life Application:** Early breast cancer detection in hospitals, assisting pathologists, supporting medical research, drug development, and public health initiatives.
