# Stroke Detection Using AI Models and CT Imaging

This project applies deep learning techniques to detect brain strokes from non-contrast CT scans. It is developed as part of a senior research project at Imam AbdulRahman Bin Faisal University, aiming to assist healthcare professionals with fast and reliable stroke diagnosis.

## 📌 Project Objective

To build interpretable and accurate AI models capable of identifying early signs of ischemic and hemorrhagic strokes in CT brain images, helping improve clinical decision-making and patient outcomes.

## 🧠 Models Included

The repository contains code, trained models, and documentation for the following architectures:

- `3DResNet-50`: Captures spatial information from CT volume slices.
- `EfficientNet-B3`: Balances performance and efficiency with compound scaling.
- `MobileNetV2`: Lightweight model optimized for speed with good accuracy.
- `ResNet-18`: Classic deep residual network suitable for medical image classification.

## 🧪 Dataset

The models are trained on anonymized CT scan data provided by King Fahad University Hospital. The dataset includes over 15,000 scans labeled for stroke or normal conditions.

> ⚠️ Due to privacy regulations, the dataset is **not** included in this repository.

## 📈 Evaluation Metrics

Models were compared based on:
- Accuracy
- Precision
- Recall
- F1-Score

Results showed strong performance across all models, with EfficientNet-B3 and ResNet-18 achieving high classification accuracy.

## 🌐 Web Interface

A simple web application, **StrokeAlert**, was developed to allow users to upload CT images and receive model predictions instantly.

## 👥 Contributors

- Zahra Jasem Al Abbadi
- Fatimah Salman Alghryafi
- Raghad Tariq Baqer
- Zainab Habib Almahal
- Fatimah Ali AlMutawa

Supervised by: Dr. Salma Alzahrani

## 📄 License

This project is for academic and research purposes only. For inquiries regarding use or extension, please contact the authors via GitHub.

