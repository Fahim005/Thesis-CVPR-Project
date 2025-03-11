
#Urban Flood Detection Using Deep Learning

Overview
Urban waterlogging has become a critical issue due to frequent flooding, making real-time flood detection essential for urban management. This project explores deep learning techniques, specifically leveraging InceptionV3, to detect urban floods from images. The study compares different models (VGG16, ResNet50, MobileNet, and InceptionV3) and highlights InceptionV3’s superior performance in flood detection tasks.

Key Features
Utilizes InceptionV3 for flood detection with transfer learning.
Achieves 98.50% accuracy, 0.98F1-score, and high precision-recall scores.
Fine-tuned last layers for urban flood images.
Real-time detection potential using CCTV, mobile, or public image sources.
Can integrate with Google Maps API for flood alerts and traffic management.

Project Scope
This project aims to develop a deep learning-based flood detection system that can be deployed in real-time. By analyzing images from CCTV cameras or mobile devices, the system can detect flood conditions and notify residents and authorities, minimizing the impact of urban flooding.

Future Applications
Integration with traffic-monitoring CCTV cameras
Automated flood alerts using Google Maps API
Enhancing urban disaster management with AI-powered insights

Dataset
The dataset consists of urban flood images used for training and testing the model. Due to size constraints, the dataset is hosted externally. You can download it from  https://drive.google.com/drive/folders/150XJE5v8wfaUjGFoCZHPqsgfvpLFT1Lu?usp=sharing

Model Training & Evaluation
Transfer learning with pre-trained InceptionV3 (ImageNet weights)
Modified architecture with Global Average Pooling & Dropout layers
Fine-tuned last layers to adapt to urban flooding images

Results
📊 Accuracy: 98.50%
📊 F1 Score: 0.98
📊 Precision: 0.96
📊 Recall: 1.0



