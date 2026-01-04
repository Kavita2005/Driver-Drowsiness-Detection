# Driver Drowsiness Detection System  

## Description  
The Driver Drowsiness Detection System is a computer vision-based application designed to enhance road safety by monitoring a driver’s eyes and detecting signs of fatigue. If drowsiness is detected, the system triggers an alert to prevent accidents.  

This project is especially useful for long-distance drivers, transport companies, and vehicle safety systems.  

---

## Features  
- Real-time monitoring of driver’s eyes using webcam or external camera  
- Eye landmark detection for identifying drowsiness  
- Alerts (sound/beep) when the driver is found to be sleepy  
- Lightweight and easy-to-deploy system  
- Works with OpenCV and Dlib facial landmark detection  

---

## Tech Stack  
- **Programming Language**: Python  
- **Libraries**: OpenCV, Dlib, Imutils, Numpy, Scipy  
- **Hardware**: Webcam or external camera  

---

## Project Structure

```
DriverDrowsinessSystem/
│
├── models/
│   └── shape_predictor_68_face_landmarks.dat   # Pre-trained ML model
│
├── Drowsiness_Detection.py    # Main Python script
├── music.wav                 # Alert sound file
├── requirements.txt          # Python dependencies
└── README.md                 # Documentation
```

## Getting Started

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/DriverDrowsinessSystem.git
cd DriverDrowsinessSystem
```

### 2️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Program

```bash
python Drowsiness_Detection.py

```




