# Skin Disease Classification Using Deep Learning

## 📌 Project Overview
This project uses Deep Learning to classify skin disease images into four categories using the MobileNetV2 model.

The model is trained using TensorFlow and Google Colab.

## 🎯 Objectives
- Classify skin disease images into four categories.
- Train an image classification model using MobileNetV2.
- Evaluate model performance using validation accuracy.
- Save the trained model for future predictions.

## 📂 Dataset
The dataset contains four classes:

1. Chickenpox
2. Measles
3. Monkeypox
4. Normal

**Total Images:** 1,429

## 🛠️ Technologies Used
- Python
- Google Colab
- TensorFlow
- Keras
- MobileNetV2
- Matplotlib
- Scikit-learn

## 🧠 Model Architecture
This project uses MobileNetV2 with Transfer Learning.

- Input Image Size: 224 × 224
- Base Model: MobileNetV2
- Pre-trained Weights: ImageNet
- Global Average Pooling
- Dropout: 0.3
- Output Layer: Softmax (4 Classes)
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 15

## 📊 Model Performance

**Validation Accuracy: 94.74%**

Validation Loss: 0.1714

The model achieved approximately 94.74% validation accuracy on the validation dataset.

## 🚀 How to Run the Project

1. Open Google Colab.
2. Upload the dataset ZIP file.
3. Extract the dataset.
4. Install the required libraries.
5. Load and preprocess the images.
6. Build the MobileNetV2 model.
7. Train the model.
8. Evaluate the model.
9. Save the trained model.

## 📌 Future Improvements
- Test the model on an independent dataset.
- Improve model generalization.
- Add a user-friendly web interface.
- Implement image upload and prediction functionality.
