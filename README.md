# 🌿 Medicinal Herb Classification using MobileNetV2

A deep learning project for classifying medicinal herbs using a Convolutional Neural Network (CNN) based on the MobileNetV2 architecture. The model leverages transfer learning and fine-tuning to achieve accurate herb recognition from images.

## 🚀 Features

* 🌿 Medicinal Herb Image Classification
* 🧠 Transfer Learning with MobileNetV2
* ⚡ Fine-Tuning for Improved Accuracy
* 📊 Confusion Matrix Visualization
* 📈 Classification Report Generation
* 🖼️ Automatic Image Preprocessing
* 🔍 Multi-Class Classification Support

## 🏗️ Model Architecture

The project uses **MobileNetV2** pretrained on ImageNet as the feature extractor.

### Architecture Components

* MobileNetV2 Backbone
* Global Average Pooling Layer
* Dropout Layer (0.3)
* Dense Softmax Classification Layer

### Training Strategy

1. Feature Extraction Phase

   * Freeze pretrained layers
   * Train classification head

2. Fine-Tuning Phase

   * Unfreeze top layers
   * Train with a low learning rate
   * Improve feature adaptation for herb classification

## 📂 Dataset Structure

```text
CNN/
├── Train/
├── Val/
└── Test/
```

The dataset consists of herb images divided into:

* Training Set
* Validation Set
* Testing Set

## 📊 Evaluation Metrics

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score
* Classification Report

## 🛠️ Tech Stack

* Python
* TensorFlow
* Keras
* MobileNetV2
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## 🔬 Workflow

1. Upload and extract dataset
2. Preprocess images
3. Convert images to RGB format
4. Generate training, validation, and test datasets
5. Train MobileNetV2 classifier
6. Fine-tune pretrained layers
7. Evaluate model performance
8. Generate confusion matrix and classification report

## 🎯 Applications

* Medicinal Plant Identification
* Herbal Research
* Agricultural Automation
* Educational Tools
* Biodiversity Monitoring

## 🔮 Future Improvements

* Real-time herb recognition
* Larger herb species dataset
* Advanced CNN architectures comparison
