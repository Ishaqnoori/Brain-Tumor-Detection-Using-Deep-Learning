# Brain-Tumor-Detection-Using-Deep-Learning
Deep learning uses Convolutional Neural Networks (CNN) to detect brain tumors. This system classifies MRI images and helps doctors diagnose tumors earlier.
This project presents a deep learning-based system for brain tumor image segmentation using a U-Net architecture. The model analyzes MRI images from the BRATS dataset and accurately identifies tumor regions. It utilizes Convolutional Neural Networks (CNN) with an encoder, decoder structure and skip connections to capture both spatial and contextual information from medical images. The primary evaluation metric for segmentation accuracy is the Dice Similarity Coefficient.

The application features a user-friendly graphical interface created with Tkinter. This interface allows users to upload datasets, generate and load the trained model, perform tumor segmentation on test images, and visualize results. The segmented tumor regions are highlighted and shown alongside the original MRI scans. The system also provides a Dice score graph to assess model performance during training. This project shows how deep learning techniques can be used in medical image analysis for automated and accurate brain tumor detection.

To Use This:
git clone https://github.com/Ishaqnoori/Brain-Tumor-Detection-Using-Deep-Learning.git
cd Brain-Tumor-Detection-Using-Deep-Learning
pip install -r requirements.txt
python BrainTumour.py
