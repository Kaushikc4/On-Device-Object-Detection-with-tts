# On-Device Object Detection for the Visually Impaired

This project aims to assist visually impaired individuals by providing an on-device object detection application. The app uses a YOLOv8 model, trained on the PASCAL VOC dataset, and converted into TensorFlow Lite (tflite) format. The Android app, developed in Kotlin, includes Text-to-Speech (TTS) functionality to announce detected objects to the user.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Model Training and Conversion](#model-training-and-conversion)


## Introduction
Visually impaired individuals often face challenges in identifying objects in their environment. This project leverages advanced object detection technology to create a user-friendly Android application that assists in object identification through audio feedback.

## Features
- **Real-time Object Detection:** Uses the YOLOv8 model for accurate and efficient object detection.
- **On-Device Processing:** Runs entirely on-device, ensuring privacy and offline functionality.
- **Text-to-Speech (TTS):** Announces detected objects to the user, providing an intuitive and accessible experience.
- **User-Friendly Interface:** Simple and accessible UI designed for ease of use by visually impaired individuals.

## Technologies Used
- **YOLOv8:** State-of-the-art object detection model.
- **PASCAL VOC Dataset:** Comprehensive dataset for training object detection models.
- **TensorFlow Lite:** Lightweight version of TensorFlow designed for mobile and embedded devices.
- **Kotlin:** Modern, concise, and safe programming language for Android development.
- **Android Text-to-Speech API:** Provides speech output capabilities for the app.

## Model Training and Conversion
### Training YOLOv8 Model:
- The YOLOv8 model is trained using the PASCAL VOC dataset, which contains a diverse set of object categories.
- Ensure the model achieves high accuracy and efficiency suitable for real-time detection on mobile devices.

### Converting to TensorFlow Lite:
- The trained YOLOv8 model is converted into TensorFlow Lite format for on-device inference.
- Use TensorFlow Lite Converter and optimize the model for better performance on mobile devices.


