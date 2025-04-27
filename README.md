
# 📷 Real-Time Object Detection with YOLOv8 and Webcam

## Overview

This project demonstrates **real-time object detection** using the **YOLOv8 (You Only Look Once)** algorithm. It captures live video from a webcam, performs object detection, and displays bounding boxes with labels and confidence scores for the detected objects.

Built with **Python**, **OpenCV**, and the **Ultralytics YOLOv8** library, this project allows you to set up and run object detection on your webcam feed.

---

## 🚀 Project Highlights

- **YOLOv8**: A state-of-the-art real-time object detection model.
- **Real-Time Processing**: Uses the webcam for live detection.
- **Object Detection**: Automatically detects a variety of objects like people, cars, animals, and more.
- **Easy to Use**: Simple setup and installation with clear instructions.

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **OpenCV**: For webcam handling and image processing.
- **Ultralytics YOLOv8**: Pre-trained YOLOv8 model for object detection.
- **Visual Studio Code**: IDE for development and debugging.

---

## 📂 Project Structure

```
Object-Detection-Using-YOLO/
├── README.md
├── yolo_dl.py
├── weights/
│   └── yolov8n.pt
```

- `README.md`: Documentation for the project.
- `yolo_dl.py`: Python script that handles webcam feed and object detection.
- `weights/yolov8n.pt`: YOLOv8 pre-trained model weights.

---

## 🔥 How to Run the Project

### 1. Clone the Repository

Clone the repository to your local machine using the following command:
```bash
git clone https://github.com/Gayathri-Juluri/Object-Detection-Using-YOLO.git
```

Navigate to the project directory:
```bash
cd Object-Detection-Using-YOLO
```

### 2. Install Dependencies

Install the required dependencies:
```bash
pip install opencv-python ultralytics
```

Alternatively, you can use a `requirements.txt` file if you have one.

### 3. Download YOLO Weights

- Download the **YOLOv8** model weights (`yolov8n.pt`) and place them in the `weights/` folder.

### 4. Run the Code

Execute the main Python script to start object detection:
```bash
python yolo_dl.py
```

### 5. Exit the Webcam Feed

To stop the object detection loop, press `'q'` while the webcam window is open.

---

## 📸 Sample Output

Here is an example of how the webcam window will appear with detected objects, labeled with their class names and confidence scores.

*(Insert a screenshot or gif showing webcam detection here)*

---

## 🧠 What You Will Learn

- How to use OpenCV to capture webcam frames.
- How to load and apply a pre-trained YOLOv8 model for real-time object detection.
- How to visualize object detection results by drawing bounding boxes and labels.

---

## 📝 Notes

- Ensure that your webcam is connected and accessible for the script.
- If you move or rename the model weights file, make sure to update the path in the code:
  ```python
  model = YOLO("weights/yolov8n.pt")
  ```

---

## 💬 Contact

For any questions or further assistance, feel free to reach out to me on [LinkedIn](https://linkedin.com/in/your-profile).

---

# 💛 Happy Coding and Object Detecting!
