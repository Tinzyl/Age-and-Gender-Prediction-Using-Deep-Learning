# 👶👦👩‍🦳 Age and Gender Prediction Using Deep Learning

This project implements a deep learning solution to predict **age** and **gender** from grayscale images using custom Convolutional Neural Networks (CNNs). The model achieves high accuracy for gender classification and competitive results for age prediction.

---

## 🌟 Project Highlights

- **Preprocessing**: Converted images to grayscale, resized them to 128x128, and normalized pixel values. 🖼️
- **Custom CNN Architectures**: Developed separate CNN models for age and gender prediction. 🤖
- **High Accuracy**: Achieved over **96% accuracy** for gender classification. 📈
- **Performance Metrics**: Evaluated age prediction using R² score and gender using confusion matrix. 🎯

---

📊 **Data Overview**

Dataset:

CSV Files:

train_age.csv: Contains imageId and age.

train_gender.csv: Contains imageId and gender.

Images: Grayscale images for each imageId.

🤖 **Model Details**

Gender Prediction Model

Architecture:

Input Layer: 128x128 grayscale image

CNN Blocks: 6 convolution layers with max-pooling, batch normalization, and ReLU activation

Global Average Pooling + Dense Layer

Output: Binary classification (Male/Female)

Accuracy: 96.1%

Age Prediction Model

Architecture:

Input Layer: 128x128 grayscale image

CNN Blocks: Similar to gender model with additional dense layers for regression

Output: Single neuron for age prediction

R² Score: 80.1%
