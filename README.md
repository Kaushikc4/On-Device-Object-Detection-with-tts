# On-Device Object Detection for the Visually Impaired

This project aims to assist visually impaired individuals by providing an on-device object detection application. The app uses a YOLOv8 model, trained on the PASCAL VOC dataset, and converted into TensorFlow Lite (tflite) format. The Android app, developed in Kotlin, includes Text-to-Speech (TTS) functionality to announce detected objects to the user.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Model Training and Conversion](#model-training-and-conversion)
- [Android App Development](#android-app-development)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Visually impaired individuals often face challenges in identifying objects in their environment. This project leverages advanced object detection technology to create a user-friendly Android application that assists in object identification through audio feedback.

## Features

- **Real-time Object Detection**: Uses the YOLOv8 model for accurate and efficient object detection.
- **On-Device Processing**: Runs entirely on-device, ensuring privacy and offline functionality.
- **Text-to-Speech (TTS)**: Announces detected objects to the user, providing an intuitive and accessible experience.
- **User-Friendly Interface**: Simple and accessible UI designed for ease of use by visually impaired individuals.

## Technologies Used

- **YOLOv8**: State-of-the-art object detection model.
- **PASCAL VOC Dataset**: Comprehensive dataset for training object detection models.
- **TensorFlow Lite**: Lightweight version of TensorFlow designed for mobile and embedded devices.
- **Kotlin**: Modern, concise, and safe programming language for Android development.
- **Android Text-to-Speech API**: Provides speech output capabilities for the app.

## Model Training and Conversion

1. **Training YOLOv8 Model**:
   - The YOLOv8 model is trained using the PASCAL VOC dataset, which contains a diverse set of object categories.
   - Ensure the model achieves high accuracy and efficiency suitable for real-time detection on mobile devices.

2. **Converting to TensorFlow Lite**:
   - The trained YOLOv8 model is converted into TensorFlow Lite format for on-device inference.
   - Use TensorFlow Lite Converter and optimize the model for better performance on mobile devices.

## Android App Development

1. **Setting Up the Project**:
   - Develop the Android application using Kotlin.
   - Integrate the TensorFlow Lite model into the Android app for real-time object detection.

2. **Implementing Object Detection**:
   - Utilize TensorFlow Lite Interpreter to run inference on the input images.
   - Process the output to identify detected objects and their locations.

3. **Text-to-Speech Integration**:
   - Use the Android Text-to-Speech API to convert detected object names into speech.
   - Ensure clear and understandable audio output for the user.

4. **User Interface**:
   - Design an accessible and straightforward interface.
   - Implement necessary permissions and features to assist visually impaired users.

## Installation

### Prerequisites

- Android Studio installed on your development machine.
- A physical Android device or an emulator with Camera support.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/on-device-object-detection.git
   cd on-device-object-detection
