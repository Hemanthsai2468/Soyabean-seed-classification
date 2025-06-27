# 🌱 Soya Seed Classification using Deep Learning

This project focuses on classifying soybean seed images into five quality-based categories using a Convolutional Neural Network (CNN) model built with TensorFlow/Keras.

## 🔍 Classes Detected
- Broken soybeans  
- Immature soybeans  
- Intact soybeans  
- Skin-damaged soybeans  
- Spotted soybeans

## 🧠 Model Overview
The CNN model is trained to recognize and classify images of soybean seeds into one of the five predefined categories. It uses image preprocessing, data augmentation, and categorical cross-entropy loss for multi-class classification.

### 🏗️ Steps Covered:
- Image data loading and augmentation  
- CNN model building using Keras  
- Training on labeled image dataset  
- Model evaluation using accuracy and classification report  
- Model saved as `soy_model.h5`

## 📁 Dataset Structure
Images are organized into the following directory structure:

dataset/  
├── train/  
│   ├── Broken soybeans/  
│   ├── Immature soybeans/  
│   ├── Intact soybeans/  
│   ├── Skin-damaged soybeans/  
│   └── Spotted soybeans/  
├── val/  
└── test/

Each folder should contain images of the respective class.

## 🛠️ Requirements
Install the required libraries:

pip install tensorflow numpy matplotlib scikit-learn pillow

## 📈 Outputs
- Accuracy and loss plots across epochs  
- Classification report and confusion matrix  
- Final saved model: `model/soy_model.h5`

## 📓 Jupyter Notebook
The complete model training pipeline is available in:

soybean_classification.ipynb

This notebook includes:  
- Data loading  
- Model training  
- Accuracy/loss graphs  
- Evaluation metrics  
- Model saving

## 🚀 Future Improvements
- Add transfer learning (e.g., MobileNetV2 or EfficientNet)  
- Increase dataset size and quality  
- Apply image preprocessing techniques like CLAHE or normalization  
- Deploy model into a web app (Flask/Streamlit)

## 📬 Contact
For queries or contributions, open an issue or reach out on GitHub:  
https://github.com/yourusername/soybean-classification
