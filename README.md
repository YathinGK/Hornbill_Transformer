# AI-Based Metadata Extraction  & Hotspot Detection for Transmission Towers

Details 
Yathin G Kummar
7019407960

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
[https://github.com/YathinGK/Hornbill Transformer.git](https://github.com/YathinGK/Hornbill_Transformer.git)

3.Execution Steps
 1. Run the MetaData_Extraction.ipynb
 2. Add the path for the Trained model and Directory of the input images
 3. RUN the program
 4. Output will be stored in folders based on the date,Type of image (Visible or Thermal) , it contains the output image that as been renamed

 4.Hotspot Detection
 1. Run the Hospot Detection.ipynb
 2. View the hotspot areas highlighted using green boxes using the Hotspot Detection Algorithm

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
