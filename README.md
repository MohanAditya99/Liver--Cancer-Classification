# Liver--Cancer-Classification
This is a neural network project to classify liver disease using the "Indian Liver Patient Dataset," which includes clinical features like age, gender, and enzyme levels. The model is trained on preprocessed and encoded data, achieving moderate accuracy and demonstrating the potential of deep learning for early liver disease diagnosis.


# Liver Disease Classification using Neural Networks 🧠

This project implements a neural network model to classify liver disease using the **Indian Liver Patient Dataset**. The dataset includes medical features such as Age, Gender, Total Bilirubin, Alkaline Phosphotase, and more, to help identify patients with liver conditions.

## 📊 Dataset Overview
- **Source**: [Indian Liver Patient Dataset (UCI Repository)](https://www.kaggle.com/datasets/uchilaka/indian-liver-patient-dataset)
- **Samples**: 583 patient records
- **Attributes**: 10 features + target label
- **Target**: 1 (liver disease) or 2 (no liver disease)

## 🧠 Model Features
- Neural Network with:
  - Input layer (10 neurons, ReLU)
  - Hidden layer (8 neurons, ReLU)
  - Output layer (2 neurons, Sigmoid)
- Trained using binary cross-entropy loss with Adam optimizer
- 100 training epochs with 20% validation split

## 📈 Results
Error rate     0.286449
Accuracy       0.713551
Loss           0.535297
Sensitivity    0.293413
Specificity    0.882212
Precision      0.500000
FPR            0.117788
MCC            0.212328
F score        0.369811

## 🔧 Workflow
1. **Data Preprocessing**:
   - Fill missing values
   - Encode categorical features (e.g., Gender)
   - Normalize and split dataset
2. **Model Training**:
   - Keras Sequential API with dense layers
   - Binary classification with performance evaluation
3. **Model Evaluation**:
   - Accuracy, precision, recall, F1-score
   - Confusion matrix visualization

## 💡 Future Enhancements
- Use CNN/RNN or ensemble methods for better performance
- Incorporate explainable AI for clinical interpretability
- Improve data balance and feature engineering

## 🛠️ Tech Stack
- Python
- Pandas, NumPy, Matplotlib
- Keras with TensorFlow backend
