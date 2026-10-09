
# AI-Based Drone Trash Detection

### Real-Time Waste Detection Using YOLOv8 and DJI Tello Drone

An AI-powered waste detection and counting system developed at **Tuwaiq Academy** using computer vision and drone technology.

The project aims to support environmental sustainability and contribute to **Saudi Vision 2030** through innovative artificial intelligence solutions.

---

## Project Overview

This project integrates a **DJI Tello Drone** with **YOLOv8** to detect, track, and count waste items in real time.

The system processes live video frames, identifies waste objects, and displays detection results with bounding boxes and unique object counts.

## Project Objectives

- Support environmental sustainability.
- Apply artificial intelligence to waste monitoring.
- Detect and track waste using computer vision.
- Count unique waste objects in real time.
- Explore solutions for smarter and cleaner cities.

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| YOLOv8 | Object detection and tracking |
| OpenCV | Image and video processing |
| DJI Tello Drone | Aerial video capture |
| DJITelloPy | Drone control and communication |

---

## How It Works

1. **Drone Connection:** Connect to the DJI Tello drone.
2. **Video Streaming:** Capture live video from the drone camera.
3. **Waste Detection:** Analyze frames using a trained YOLOv8 model.
4. **Object Tracking:** Assign tracking IDs to detected objects.
5. **Waste Counting:** Count unique tracked object IDs.
6. **Visualization:** Display detections and save the annotated video.

---

## Project Results

### Detection Using Tello Drone

Real-time waste detection and counting using the DJI Tello drone camera.

![Drone Detection](results/drone_result.jpg)

### Detection Using Laptop Camera

Additional waste detection demonstrations using a laptop camera.

![Laptop Detection](results/webcam_result.jpg)

---

## Project Structure

```text
AI-Drone-Trash-Detection/
│
├── main.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── models/
│   └── best.pt
│
└── results/
    ├── drone_result.jpg
    └── webcam_result.jpg
```

---

## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/alshehrilama74-M/AI-Drone-Trash-Detection.git
cd AI-Drone-Trash-Detection
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Prepare the Model

Place the trained YOLOv8 model (`best.pt`) inside the `models` directory.

### 4. Run the Project

Connect the computer to the DJI Tello drone and execute:

```bash
python main.py
```

**Note:** The project requires a DJI Tello drone, a compatible trained YOLOv8 model, and a safe flight environment.

The main script uses the drone camera. Laptop camera testing requires a separate implementation.

---

## Future Improvements

- Integrate GPS for waste location tracking.
- Develop a web or mobile monitoring dashboard.
- Implement automated municipality notifications.
- Improve detection and tracking accuracy.
- Explore higher-quality drone cameras.

---

## Saudi Vision 2030

This project supports the environmental sustainability goals of Saudi Vision 2030 by exploring how artificial intelligence and drone technology can improve waste monitoring and contribute to cleaner public spaces.

---

## Project Team

Developed at **Tuwaiq Academy** by:

- Leena Alonayq
- Danyah Alotaibi
- Raghad Ala'abrah
- Lama Alshehri
