# ViroVision_Faster_RCNN_ResNet50_FPN
![Status](https://img.shields.io/badge/RepoStatus-Public-green)
![Python](https://img.shields.io/badge/Python-3.11-blue)
![License](https://img.shields.io/github/license/MrRincon/ViroVision_Faster_RCNN_ResNet50_FPN)

This project focuses on developing a Convolutional Neural Network (CNN) using Faster R-CNN model for the classification and object detection of viruses in Transmission Electron Microscopy (TEM) Images. 
The goal is to accurately identify and locate individual virus particles within complex images, contributing to faster and more efficient virus analysis.

I would like to acknowledge and extend my gratitude to for the guidance and support throughout this project to my project supervisor Ahmed Eissa, Associate Lecturer in Computer Science, and Dr. Olugbenga Oluwagbeni, Senior Lecturer of Computing Science. 

---
## Dataset Reference
Shahane, S. (2021) 'Virus Image Dataset'. Available at: https://www.kaggle.com/datasets/saurabhshahane/virus-images (Accessed: 02 June 2025). Available license at: https://creativecommons.org/licenses/by/4.0/

---
## Problem Solved
Traditional methods for identifying and counting virus particles in TEM images are often manual, time-consuming, and subject to human error. 
This project addresses the challenge of automating this process by leveraging deep learning techniques. 
The Faster R-CNN model is employed to detect the presence and location of virus particles (object detection) and classify them based on their visual characteristics (classification).

---
## Motivation
The motivation behind this project arises from the need for rapid and accurate virus identification in various fields, including medical diagnostics, virology research, and outbreak surveillance. 

---
## Requirements
  ### System Specifications
    - Device: ASUS ROG Strix G713QM
    - CPU: AMD Ryzen 9 5900HX (16 cores, ~3.3 GHz)
    - RAM: 16 GB
    - GPU: NVIDIA GeForce RTX 3060 Laptop GPU (6 GB VRAM)
    - Operating System: Windows 11 Home 64-bit (Build 26100)
    - Python Version: 3.11.7 (Anaconda distribution)
  ### Software Setup
    - Install Anaconda (Python 3.11+ recommended)
    - Launch JupyterLab via Anaconda Navigator
    - Use a Python 3 kernel in JupyterLab
  ### Project Setup Instructions
    - Clone the repository
    - Download the dataset from Kaggle and place the context_virus_RAW folder inside the root directory of the cloned repository
    - Run initial code cells to install all required libraries 
    - Restart the kernel after installations complete
    - Run the remaining cells sequentially
    - DO NOT modify the README.md, .gitignore, and LICENSE Files to maintain repository integrity
    
---
## Table of Contents
1. Project Overview
2. Dataset Reference
3. Problem solved
4. Motivation
5. Requirements
   - System Specifications
   - Software Setup
   - Project Setup Instructions
6. Notebook Structure
   - Libraries Installation and Restarting the Kernel
   - Data Directories Check-Up and Data Extraction
     - Setting Up the Libraries
     - Directories, Images, and Files Check-Up
     - Extracting and Normalising the Data
     - Augmenting the Training Dataset for Balance
     - Transforming Data into COCO Format
   - Training the Faster R-CNN Model
     - Adding All the Libraries
     - Using the Data From the COCO JSON Files
     - Loading, Modifying, and Visualising the Pretrained Faster R-CNN
     - Training the Model
     - Testing and Predictions
     - Model Evaluation 
