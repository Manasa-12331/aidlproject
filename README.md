🦴 Knee Osteoarthritis Severity Detection

This project aims to classify knee X-ray images into three severity levels of Osteoarthritis: Healthy, Moderate, and Severe. We leverage both custom CNN architectures and transfer learning with EfficientNetB5 to achieve high classification performance.

🚀 Project Objectives

Build a baseline CNN model for multiclass classification

Improve performance using deeper custom CNNs

Apply EfficientNetB5 (transfer learning) to boost accuracy and reduce overfitting

Address class imbalance using class weights and data balancing

Evaluate and compare models using accuracy, F1-score, and confusion matrix

📁 Dataset Overview

Total images: 3,000 (balanced across 3 classes)

Image size: 224x224

Split: 70% Train, 15% Validation, 15% Test

Format: Loaded using ImageDataGenerator and flow_from_dataframe()

🧪 Evaluation Metrics

Accuracy

Precision, Recall, F1-Score (per class)

Confusion Matrix

Training & Validation Curves

👥 Team

Tarun Teja Miditana – Baseline CNN, EfficientNetB5 modeling, evaluation, and visualization

Manasa Reddy Kaitha – DenseNet121 model implementation and testing

Manideep Sai Ram Sadhu – MobileNetV3 model implementation and optimization

UNC Charlotte, Spring 2025
Graduate Program: Data Science & Business Analytics
