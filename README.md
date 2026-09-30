# Deep Learning Based Waste Image Classification System ♻️

A deep learning-based image classification system that identifies different types of waste using **TensorFlow** and **MobileNetV2 Transfer Learning**.

## 📌 Project Overview

This project uses computer vision and deep learning to classify waste images into six different categories. The model was developed and trained using Google Colab with GPU acceleration.

## 🎯 Objective

The main objective of this project is to build an image classification model that can automatically identify the type of waste from an uploaded image.

## ♻️ Waste Categories

The model classifies waste into 6 categories:

1. Cardboard
2. Glass
3. Metal
4. Paper
5. Plastic
6. Trash

## 🧠 Model

**MobileNetV2** was used as the base pre-trained model.

Transfer learning was applied using ImageNet pre-trained weights, followed by custom classification layers for the six waste categories.

### Model Configuration

- Model: MobileNetV2
- Input Image Size: 224 × 224
- Number of Classes: 6
- Training Epochs: 15
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Activation Function: Softmax
- Dropout: 0.2

## 📊 Dataset

The project uses the **TrashNet** waste image dataset.

The dataset contains images belonging to six waste categories:

- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

Total images used: **2527**

## ⚙️ Methodology

The project follows these steps:

1. Dataset collection
2. Dataset loading and exploration
3. Image resizing to 224 × 224
4. Training, validation and testing split
5. Data augmentation
6. MobileNetV2 transfer learning
7. Model training
8. Model evaluation
9. Confusion matrix and classification report
10. Prediction on new images
11. Saving and reloading the trained model

## 📈 Results

The trained model achieved:

**Test Accuracy: 85.14%**

**Test Loss: 0.4555**

The model was also tested on a new waste image and successfully produced a waste-category prediction.

## 🖼️ Example Prediction

For one uploaded test image, the model predicted:

- **Predicted Category:** Metal
- **Confidence:** 44.13%

The confidence value represents the model's predicted probability for its selected class for that particular image.

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 📂 Project Files

- `Deep_Learning_Waste_Classification.ipynb` — Complete project notebook

## 🚀 Future Scope

The project can be improved further by:

- Using a larger and more balanced dataset
- Fine-tuning the pre-trained model
- Improving performance on underrepresented classes
- Deploying the model as a web or mobile application
- Adding real-time waste image classification
- Integrating the system with smart waste-management solutions

## 👩‍💻 Author

**Niharika Sharma**

B.Tech CSE (AI & ML) Student
