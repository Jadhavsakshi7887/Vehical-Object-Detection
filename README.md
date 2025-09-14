#  Vehicle Object Detection – YOLOv8 (Bangalore Traffic)

This project demonstrates **real-time vehicle object detection** using the **YOLOv8 model**, trained on **2,000+ images** captured from **Bangalore traffic conditions**.  
The system is designed to identify and track vehicles in challenging urban traffic environments.

---

## Features
- Trained on a **custom dataset** of Bangalore traffic.  
- Detects cars, bikes, buses, trucks, auto-rickshaws, and more.  
- Built with [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics).  
- Works with **images, videos, and live webcam feeds**.  

---

##  Dataset
- **Source**: 2K+ real-time traffic images from Bangalore.  
- **Annotations**: YOLO format (`.txt` bounding boxes).  
- **Classes**:  
  1. Two-wheeler  
  2. Bus  
  3. Truck  
  4. Auto  
  5. Bicycle  
  6. MUV (Multi Utility Vehicle)  
  7. SUV (Sports Utility Vehicle)  
  8. Van  
  9. Mini-bus  
  10. Tempo  
  11. Hatch-back  
  12. Others  

---



##  Installation

Clone the repository and install the required dependencies:

```bash
# Clone this repo
git clone https://github.com/Jadhavsakshi/vehicle-object-detection.git
cd vehicle-object-detection

# Install dependencies
pip install -r requirements.txt
