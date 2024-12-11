# P1-Image_Classification_by_Machine_Learning
Image classification project using CIFAR-10 dataset and MobileNetV2, developed as part of an AI/ML internship by TechSaksham and EduNet under AICTE. The project includes model training with TensorFlow/Keras and deployment via Streamlit for real-time image classification.

## Requirements

### Hardware Requirements:
- Processor: Intel i5 or higher (or equivalent AMD processor)
- GPU: NVIDIA GTX 1650 or higher (for faster model training)
- Memory: 8 GB RAM (preferably 16 GB for optimal performance)
- Storage: At least 10 GB of free disk space
- Internet Connectivity: Required for installing dependencies and downloading the CIFAR-10 dataset

### Software Requirements:
- Python 3.6 (preferably 3.6 or higher)
- TensorFlow 2.0
- Keras
- Streamlit
- NumPy
- Pandas
- Matplotlib
- Anaconda (optional, but recommended for managing environments)

## Installation

## Install dependencies:
  pip install -r requirements.txt

## Download the CIFAR-10 dataset:
  The CIFAR-10 dataset will be automatically downloaded by TensorFlow when running the code for the first time.

## Running the Application
  python newapp.py
  This will launch a local Streamlit server, and the application will be accessible at: http://localhost:8501
  
How the Application Works:
The user can upload an image through the Streamlit interface.
The trained MobileNetV2 model will classify the uploaded image into one of the 10 categories of the CIFAR-10 dataset.
The predicted class and confidence score will be displayed in the web interface.

Model Training
The model is built using TensorFlow and Keras with the MobileNetV2 architecture. It is trained using the CIFAR-10 dataset, and data augmentation techniques are applied to prevent overfitting. The model is evaluated on a test dataset, and performance is measured using accuracy and loss.


   
