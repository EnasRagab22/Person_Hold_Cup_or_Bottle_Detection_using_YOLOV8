# 🧠 Person Holding Cup or Bottle Detection using YOLOv8

This project leverages **YOLOv8** (You Only Look Once) to detect if a person is holding a cup or bottle in images, videos, or webcam feeds. Built with Ultralytics' YOLO implementation for state-of-the-art real-time object detection.

---

## 📌 Features

- ✅ Detects people holding cups or bottles  
- 📸 Supports **images**, **videos**, and **webcam** feeds  
- 🧠 Built using **YOLOv8** from [Ultralytics](https://github.com/ultralytics/ultralytics)  
- 💡 Ideal for behavior recognition, surveillance, and retail analytics  

---

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/EnasRagab22/Person_Hold_Cup_or_Bottle_Detection_using_YOLOV8.git
   cd Person_Hold_Cup_or_Bottle_Detection_using_YOLOV8
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

### 📓 Using the Jupyter Notebook
Open `Person_Hold_Cup_or_Bottle_Detection_using_YOLOV8.ipynb` and execute the cells to:  
- Load the pre-trained model  
- Perform detection on images/videos  
- Annotate and visualize results  

### 💻 Using the YOLOv8 CLI

#### Train the Model
```bash
yolo task=detect mode=train model=yolov8n.pt data=data.yaml epochs=50 imgsz=640
```

#### Run Inference on Media Files
```bash
yolo task=detect mode=predict model=runs/detect/train/weights/best.pt source=your_media_file
```

---

## 📂 Project Structure

```
Person_Hold_Cup_or_Bottle_Detection_using_YOLOV8/
├── data/                  # Training/validation datasets (images + labels)
├── runs/                  # Output directories for training/detection results
├── Person_Hold_Cup_or_Bottle_Detection_using_YOLOV8.ipynb  # Main Jupyter notebook
├── requirements.txt       # Dependency list
└── README.md              # Project documentation
```

---

## 🧠 Model Details

- **Base Model**: `yolov8n.pt` (YOLOv8 Nano)  
- **Classes**: `person`, `cup`, `bottle`  
- **Dataset**: Custom dataset in YOLO format  
- **Training Configuration**:  
  - Epochs: 50  
  - Image Size: 640x640  

---

## 📊 Example Results

*(Add screenshots or GIFs of detection outputs here)*  
Example format:  
![Detection Example](path/to/example_image.jpg "Detection Result")

---

## 🙌 Acknowledgements

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)  
- [OpenCV](https://opencv.org/) for image processing  
- Python community for foundational libraries  

---

## 📜 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 👩💻 Author

**Enas Ragab**  
- GitHub: [@EnasRagab22](https://github.com/EnasRagab22)  
``` 

### Key Improvements:
- Organized sections hierarchically for better flow  
- Standardized emoji usage and formatting  
- Added syntax highlighting for code blocks  
- Clarified project structure with a plain-text tree  
- Added placeholders for example results  
- Improved consistency in bullet points and headers  
- Simplified installation/usage instructions  
- Enhanced readability through spacing and indentation
