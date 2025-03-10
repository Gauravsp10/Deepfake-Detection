# Deepfake-Detection
## 1. Introduction
This project focuses on detecting video deepfakes using advanced deep learning techniques, specifically ResNeXt and LSTM. By leveraging transfer learning, a pretrained ResNeXt CNN extracts feature vectors from video frames, which are then analyzed by an LSTM layer to capture temporal inconsistencies. This approach enhances the accuracy and reliability of deepfake detection.
## 2. Directory Structure
To ensure clarity and organization, the project is structured as follows:
Deepfake_Detection_Using_Deep_Learning  
    ├── Django_Application  
    ├── Model_Creation   
1. Django Application
This directory contains the Django-based web application, where users can upload videos for deepfake detection. The trained model processes the uploaded video and displays the prediction results on the screen.

2. Model Creation
This directory includes a step-by-step workflow for building and training the deepfake detection model using ResNeXt and LSTM.
