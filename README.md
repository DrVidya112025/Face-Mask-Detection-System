🖥️  Face Mask Detection System Using Python and OpenCV

📌 Overview
The Face Mask Detection System is a computer vision application developed using Python, OpenCV, and deep learning models. It helps in detecting whether a person is wearing a face mask or not in real-time using webcam video feed. This is particularly useful for ensuring public safety during health crises like the COVID-19 pandemic.The main goal of the project is to detect and classify .whether a person is wearing a mask or not using a streamlit web environment. It is an object detection and classification problem with two different classes (Mask and Without Mask). A hybrid model using deep machine learning for detecting face mask will be presented. A dataset is used to build this face mask detector using Python, OpenCV, and TensorFlow and Keras.In order to ensure that people wear masks while coming to work we hope this module will be helpful in detecting it.This project is useful for applications such as an effective face mask detection  during COVID 19.

🎯 Features
Real-time face detection via webcam

Face mask classification (Mask / No Mask)

Uses deep learning algorithm such as CNN for accurate detection

📁 Dataset
This dataset consists of  Train and Test of 4095 images belonging to two classes :

with_mask: 2165 images
without_mask: 1930 images
The images used were real images of faces wearing masks.

🧰 Technologies Used

Python

OpenCV

TensorFlow / Keras (CNN model)

NumPy

Haar Cascade Classifier (for face detection)

🖼️ Screenshots







🔧 Prerequisites
All the dependencies and required libraries are included in the file requirements.txt

💻 Installation

git clone https://github.com/yourusername/face-mask-detection.git
cd face-mask-detection
pip install -r requirements.txt

▶️ Run the Application

💡 Steps to follow:
1.Install all the necessary libraries such as pillow,scipy and tensor flow.
2.Create a train.py file in the virtual environment of myprojects folder under the script folder.
3.Write the source code in train.py.
4.In cmd: activate the train.py
5.Run the train.py
6.Check the accuracy of the trained model
7.Save the file as mask.h5.


🗂️ File Structure

face-mask-detection/
│
├── dataset/              # Dataset (images with mask / without mask)
├── model/                # Saved trained model
├── detect_mask_video.py  # Main script for webcam detection
├── train_model.py        # Script to train the model
├── requirements.txt
└── README.md

🔑 Results

Our model gave 98% accuracy for Face Mask Detection after training

📌 Use Case
Public entry points like malls, offices, and hospitals

Automated monitoring in CCTV camera feeds

Support staff to ensure compliance without manual checks

📖 References

OpenCV Documentation

TensorFlow Keras

Dataset from Kaggle
