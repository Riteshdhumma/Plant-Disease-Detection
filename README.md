Plant Disease Detection using Deep Learning
Overview

This project is a Deep Learning-based Plant Disease Detection System developed using TensorFlow and Keras. The model is trained on leaf images from the PlantVillage dataset and can identify plant diseases from images of plant leaves.

The trained model is also converted to TensorFlow Lite (TFLite), making it suitable for deployment in Android and edge-device applications.

Features
Plant disease classification using CNNs
Image preprocessing and augmentation
TensorFlow/Keras model training
TensorFlow Lite model conversion
Mobile deployment ready
High accuracy disease prediction
Scalable for additional crops and diseases
Project Structure
plant-disease-detection/
│
├── plant_detection_Model.ipynb
├── plant_disease_model.keras
├── plant_disease_model.tflite
├── requirements.txt
├── README.md
└── screenshots/
Technologies Used
Python
TensorFlow
Keras
NumPy
Matplotlib
OpenCV
Jupyter Notebook
Dataset

This project uses the PlantVillage dataset for training and evaluation.

Note: The dataset is not included in this repository due to its large size.

Model Pipeline
Dataset Collection
Data Preprocessing
Data Augmentation
CNN Model Training
Model Evaluation
TensorFlow Lite Conversion
Deployment Ready Model Generation

TensorFlow Lite Deployment

The trained model has been exported to TensorFlow Lite format:

plant_disease_model.tflite

This model can be integrated into Android applications for real-time plant disease detection.
