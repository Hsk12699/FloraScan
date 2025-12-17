# FloraScan

FloraScan is a mobile application developed for Android using Kotlin and TensorFlow that predicts flower species from images captured through the device camera. The application integrates deep learning–based image classification with a clean and dynamic UI, focusing on accuracy, performance, and seamless navigation.


## Project Overview

FloraScan leverages multiple deep learning architectures to perform real-time flower identification on mobile devices. A custom Convolutional Neural Network (CNN) was engineered and optimized to achieve high classification accuracy, outperforming commonly used pretrained models.

The application follows a modular architecture using Android Fragments, ensuring smooth navigation and efficient UI state management. Real-time image processing enables fast and reliable predictions directly within the app.


## Wireframe Design

The wireframe outlines the overall application flow, screen layout, and navigation structure, serving as the foundation for the final UI implementation.

<img width="1852" height="1136" alt="Wireframe (2)" src="https://github.com/user-attachments/assets/4e595c5a-0f8e-45ab-a4a9-4edf774f40f2" />


## System Architecture

The system architecture is designed to support efficient mobile inference and smooth user interaction. It consists of image capture, preprocessing, deep learning inference, and result visualization layers.

<img width="4233" height="4233" alt="Application Architecture (1)" src="https://github.com/user-attachments/assets/998dfe80-66b8-469f-aab9-7417980d17ab" />


## Key Features

- Real-time flower identification using camera-captured images  
- Custom CNN model with superior classification performance  
- Performance comparison with EfficientNet and MobileNetV2  
- Fragment-based UI architecture for seamless navigation  
- Optimized for efficient mobile performance  


## Technologies Used

### Mobile Development
- Kotlin
- Android Studio
- Android Fragments

### Deep Learning and Machine Learning
- TensorFlow
- Keras
- Convolutional Neural Networks
- Transfer Learning

### Libraries and Tools
- NumPy
- OpenCV
- Matplotlib


## Dataset

The model was trained and evaluated using the Flowers Recognition dataset from Kaggle.

Dataset link:  
https://www.kaggle.com/datasets/alxmamaev/flowers-recognition

Dataset details:
- 4,242 images
- Five flower classes


## Results

| Model          | Accuracy |
|---------------|----------|
| Custom CNN     | 93.19%   |
| MobileNetV2    | 92.10%   |
| EfficientNet   | 82.50%   |


## Screenshots

### Application UI
<img width="1945" height="1282" alt="App UI (1)" src="https://github.com/user-attachments/assets/38b5a1a5-63bc-4250-a8a6-aa6a298355c4" />

### Prediction Output
<img width="1403" height="1144" alt="App Output UI" src="https://github.com/user-attachments/assets/19f34bf5-f387-4bfc-8f28-47e1c1b632e4" />


## Future Enhancements

- Implement an ensemble learning approach combining CNN, MobileNetV2, and EfficientNet  
- Improve inference speed for low-end mobile devices  
- Extend classification to additional flower species  
- Add prediction confidence scores and explainability techniques such as Grad-CAM
