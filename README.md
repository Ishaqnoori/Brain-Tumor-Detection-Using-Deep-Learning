# Brain-Tumor-Detection-Using-Deep-Learning
Deep learning uses Convolutional Neural Networks (CNN) to detect brain tumors. This system classifies MRI images and helps doctors diagnose tumors earlier.
This project presents a deep learning-based system for brain tumor image segmentation using a U-Net architecture. The model analyzes MRI images from the BRATS dataset and accurately identifies tumor regions. It utilizes Convolutional Neural Networks (CNN) with an encoder, decoder structure and skip connections to capture both spatial and contextual information from medical images. The primary evaluation metric for segmentation accuracy is the Dice Similarity Coefficient.

Project Overview:
This project implements a Deep Learning-based Brain Tumor Segmentation System using a U-Net Convolutional Neural Network architecture. The model is trained on MRI images (BRATS dataset) to accurately segment tumor regions using the Dice Similarity Coefficient as the evaluation metric.
A graphical user interface (GUI) built with Tkinter allows users to:
Load the dataset
Generate / Load pre-trained CNN & U-Net model
Upload test MRI images
Perform tumor segmentation
Visualize Dice Similarity score graph
This project demonstrates the application of deep learning in medical image segmentation.

Key Features:
U-Net based CNN architecture
Dice Coefficient Loss Function
Pre-trained model loading
MRI tumor segmentation
GUI-based execution
Dice Similarity Graph visualization

Technologies Used:
Python 3.7.10
TensorFlow 1.14.0
Keras 2.3.1
OpenCV
NumPy
Matplotlib
Scikit-learn
Tkinter
or U can Check the requirements.txt for the specific versions of the modules.

Installation:
1.Clone Repository
git clone https://github.com/Ishaqnoori/Brain-Tumor-Detection-Using-Deep-Learning.git
cd Brain-Tumor-Detection-Using-Deep-Learning
2️.Create Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate
3️.Install Dependencies
pip install -r requirements.txt
4.Running the Project
python BrainTumour.py
