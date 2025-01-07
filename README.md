# sign language recognition 
![image](https://github.com/user-attachments/assets/ca9532c8-1994-438e-a697-120be3a69bac)
   
click for detailed view->https://drive.google.com/drive/folders/1cl_NWVaIr6ikTah1B6-qlWp2vQNikJ1y?usp=sharing
## Sign Language Recognition using CNN
### Overview
This project aims to build a Sign Language Recognition system using Convolutional Neural Networks (CNN) to classify sign language gestures and recognize specific words of your choice. The system includes a Graphical User Interface (GUI) that allows users to upload images or stream real-time video for sign language detection.

The model is designed to recognize various sign language gestures and provide the corresponding word or phrase. It has been trained using a dataset of sign language images, with data augmentation techniques applied to increase the robustness of the model. The model operates within a specific time window, from 6 PM to 10 PM, to enhance its functionality during specific hours.

## Features
### Image Upload: Users can upload images to detect and classify sign language gestures.
### Real-time Video Recognition: The system can recognize sign language gestures from a video stream.
### Data Augmentation: Techniques such as rotation, flipping, and scaling are used to enhance the model's generalization.
### GUI Interface: A user-friendly interface allows for easy image uploads and real-time sign language recognition.
### Time-based Operation: The model operates only between 6 PM and 10 PM, providing context-aware functionality.
### Preprocessing and Data Augmentation
### The data preprocessing pipeline includes:

Resizing the images to a standard size.
Normalization of pixel values.
Data Augmentation techniques to increase the variety of the training data, including random rotations, scaling, and flipping.
Model Architecture
A Convolutional Neural Network (CNN) has been trained on the preprocessed images to recognize hand gestures corresponding to words in sign language. The CNN architecture is designed to capture features from images at multiple levels, using layers like convolutional layers, pooling layers, and dense layers to output a classification.

###  How It Works
Upload Image: Users can upload an image of a sign language gesture.
Real-time Video: The system detects and recognizes gestures in real-time via video input.
Time-based Activation: The model is operational from 6 PM to 10 PM.
Sign Language Prediction: The system predicts the sign language gesture and displays the corresponding word.
