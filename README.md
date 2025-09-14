#  Vehicle Object Detection – YOLOv8 (Bangalore Traffic)

This project demonstrates **real-time vehicle object detection** using the **YOLOv8 model**, trained on Images captured from **Bangalore traffic conditions**.  
The system is designed to identify and track vehicles in challenging urban traffic environments.

---

## Features
- Trained on a **custom dataset** of Bangalore traffic.  
- Detects cars, bikes, buses, trucks, auto-rickshaws, and more.  
- Built with [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics).  
- Works with **images, videos, and live webcam feeds**.  

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
