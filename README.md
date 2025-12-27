# Breast_Cancer_Classification
Breast Cancer Classification using CNN (CancerNet) on IDC histology image dataset. This notebook includes data preprocessing, model training, evaluation, and visualization of results


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
