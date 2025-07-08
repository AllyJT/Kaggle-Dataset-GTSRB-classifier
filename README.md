# Kaggle-Dataset-GTSRB-classifier
This project was completed as part of a course assignment at the University of Melbourne. All code and analysis are my own.

## 📝 Overview
A traffic sign classification project using the German Traffic Sign Recognition Benchmark (GTSRB) dataset from Kaggle.  
The goal is to build a model that accurately classifies traffic signs using machine learning and image preprocessing techniques. The modelaim to achieved consistently strong performance on both the validation and test sets (>50%).

> **Note**: The course report was limited to 1800 words, so only key models and analysis were included in that version. This repo contains full implementation details.

## 📊 Dataset

- Source: [Kaggle - GTSRB Dataset](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign)
- Classes: 43 traffic sign categories
- Format: Image files with CSV metadata

> **Note**: Dataset files are not included in this repository due to size and licensing.  
You can download the dataset from the [Kaggle page](https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign).

## ⚙️ Methods

- **Image Preprocessing**:
  - Histogram of Oriented Gradients (HOG)
  - Color histograms (use the provided data from kaggle)
  - PCA for dimensionality reduction (use the provided data from kaggle)

- **Models Tried**:
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Random Forest (RF)

- **Evaluation**:
  - Train/Test split
  - Cross-validation
  - Accuracy, confusion matrix

## 🏆 Best Results on Kaggle testing

| Model         | Features Used | Accuracy |
|---------------|---------------|----------|
| SVM           | HOG            | ~94.5%     |
| Random Forest | HOG            | ~93.6%     |

## 📌 Tools Used

- Python (NumPy, pandas, scikit-learn, matplotlib)
- Jupyter Notebook
- OpenCV 

