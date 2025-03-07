# AI-Based Image Classification & Hotspot Detection for Transmission Towers

Project Overview

This project automates the classification, metadata extraction, organization, and hotspot detection of transmission tower images. The system utilizes AI-based image classification to distinguish between Thermal and Visible images, organizes them based on date and geolocation, and detects hotspots in thermal images for anomaly identification. The workflow is fully automated, ensuring seamless image processing without manual intervention.
 
Key Features
1. AI-Based Image Classification
2. Metadata Extraction & Organization
3. Hotspot Detection in Thermal Images
4. Optimized Workflow & Scalability

Setup 
1.Prerequisites
pip install tensorflow opencv-python numpy pandas pillow

2.Clone the Repository
https://github.com/YathinGK/Hornbill Transformer.git

3.Execution Steps
 i)Run the MetaData_Extraction.ipynb
 ii)Add the path for the Trained model and Directory of the input images
 iii)RUN the program
 iv)Output will be stored in folders based on the date,Type of image (Visible or Thermal) , it contains the output image that as been renamed

 4.Hotspot Detection
 i)Run the Hospot Detection.ipynb
 ii)View the hotspot areas highlighted using green boxes using the Hotspot Detection Algorithm

Structure :
├── 📂 Input_Images/         
├── 📂 organized_images/      
│   ├── 📂 Classified_Images/ 
│   ├── 📂 Date_Wise_Images/  
├── 📂 Trained_Model/         
├── 📂 output/                
├── 📄 process_images.py      
├── 📄 train_model.py         
├── 📄 hotspot_detection.py   
├── 📄 metadata.csv 
