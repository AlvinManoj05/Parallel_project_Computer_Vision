# Pneumonia Detection Using CNN

## 1. Project Overview
This project aims to classify chest X-ray images into two categories:
- **NORMAL** – No pneumonia detected in the dataset label.
- **PNEUMONIA** – Pneumonia detected in the dataset label.

We use a Convolutional Neural Network (CNN) to build an image classification model.

## 2. Objectives
- Explore and understand the chest X-ray dataset.
- Preprocess images for CNN training.
- Build and train a CNN model.
- Evaluate the model using appropriate performance metrics.
- Predict the class of new chest X-ray images.

## 3. Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- GitHub

## 4. Dataset Information

Dataset Name: Dataset for CNN

Platform: Kaggle

Uploaded by: Mit Gandhi

Dataset Link: https://www.kaggle.com/datasets/mitgandhi10/dataset-for-cnn

Classes Used:

- NORMAL
- PNEUMONIA

Dataset Distribution:

Dataset| NORMAL| PNEUMONIA| Total
Training| 74| 74| 148
Testing| 20| 20| 40
Total| 94| 94| 188

Note: We use this dataset for educational purposes. Please check the original Kaggle dataset's licence and terms before redistributing its images.

## 5. Data Preprocessing
The following preprocessing steps are performed:
1. Dataset exploration.
2. Image inspection and corrupted-image checking.
3. Splitting the training data into training and validation sets.
4. Resizing images to 224 × 224 pixels.
5. Converting images to grayscale.
6. Normalizing pixel values between 0 and 1.
7. Preparing TensorFlow datasets for model training.

## 6. Project Structure
```text
Parallel_project_Computer_Vision/
│
├── Parallel_Project_computerVision_PneumoniaD...ipynb
└── README.md
```

## 7. Team Members
## Project Phases and Team Contributions

| Phase | Description | Assigned Member(s) |
|---|---|---|
| **Phase 1: Exploratory Data Analysis (EDA)** | Understand images, labels and class distribution. | Ananthika |
| **Phase 2: Image Preprocessing** | Resize, normalize, augment and prepare images. | Ananthika |
| **Phase 3: Model Development** | Build CNN and Transfer Learning models. | Anjima |
| **Phase 4: Model Training and Optimization** | Train, validate and improve model performance. | Aswathy |
| **Phase 5: Model Evaluation and Testing** | Test the model using unseen images. | Gautham |
| **Phase 6: Application Development** | Build an interface to predict new X-ray images. | Alvin |

## Team Members

1. Ananthika
2. Anjima
3. Aswathy
4. Gautham
5. Alvin
6. Jobil
7. Devan


## 8. Disclaimer
This project is developed for educational purposes only. It is not intended for clinical diagnosis or medical decision-making.
