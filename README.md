#  Vehicle Object Detection – YOLOv8 (Bangalore Traffic)

This project demonstrates **real-time vehicle object detection** using the **YOLOv8 model**, trained on Images captured from **Bangalore traffic conditions**.  
The system is designed to identify and track vehicles in challenging urban traffic environments.

# Additional Project Insights

This project was trained on Google Colab GPU, using a relatively small dataset of around 1,000 images. My main goal was to deeply understand how object detection models work from handling real-world traffic image data to training, evaluating, and improving models. I also experimented with different detection frameworks like Detectron2, but due to environment and compatibility issues, I ultimately used the YOLO family of models for stable training.

I spent around 1.5 months on this project, exploring different training strategies. I tested the model with and without data augmentation, and observed a clear improvement in accuracy when augmentation was applied, especially for noisy and low-light traffic images. This helped me learn how preprocessing and augmentation directly influence model robustness.

---
# Tech Stack

YOLOv8 • YOLOv9 • Ultralytics • Detectron2 (attempted) • Python • Google Colab GPU • Data Augmentation • Image Preprocessing 

## Features
- Trained on a **custom dataset** of Bangalore traffic.  
- Detects cars, bikes, buses, trucks, auto-rickshaws, and more.  
- Built with [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics).  
- Works with **images**.  

---

##  Dataset
- **Preprocessing**: prepared the dataset, including:  
  - Data cleaning and filtering noisy images  
  - Image resizing and normalization  
  - YOLO-style bounding box annotations  
  - Splitting into **train / val / test** sets  
- **Annotations**: YOLO format (`.txt` bounding boxes).  
- **Classes (15 total)**:  
  - Hatchback  
  - Sedan  
  - SUV  
  - MUV  
  - Bus  
  - Truck  
  - Three-wheeler (Auto)  
  - Two-wheeler (Bike/Scooter)  
  - LCV (Light Commercial Vehicle)  
  - Mini-bus  
  - Mini-truck  
  - Tempo-traveller  
  - Bicycle  
  - Van  
  - Others  


##  Installation

Clone the repository and install the required dependencies:

```bash
# Clone this repo
git clone https://github.com/Jadhavsakshi/vehicle-object-detection.git
cd vehicle-object-detection

# Install dependencies
pip install -r requirements.txt
