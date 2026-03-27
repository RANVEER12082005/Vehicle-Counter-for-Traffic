# Vehicle Counter for Traffic

A computer vision project that detects and counts vehicles in a traffic video using YOLOv8 and OpenCV.

## Requirements
- Python 3.10 or 3.11
- Webcam or traffic video file

## Setup Instructions

### 1. Clone the repository
git clone https://github.com/your-username/vehicle-counter
cd vehicle-counter

### 2. Create virtual environment
python -m venv venv
venv\Scripts\activate        # Windows
source venv/bin/activate     # Mac/Linux

### 3. Install dependencies
pip install -r requirements.txt

### 4. Add your video
Place your traffic video inside the `videos/` folder and name it `traffic.mp4`

### 5. Run the project
python main.py

## Output
- Processed video saved in `output/result.mp4`
- Vehicle count displayed on screen in real time

## Technologies Used
- Python
- OpenCV
- YOLOv8 (Ultralytics)
- NumPy
```

---

## STEP 11 — Final Folder Structure Check

Before running, your project should look exactly like this:
```
vehicle-counter/
│
├── videos/
│   └── traffic.mp4        ← your video here
├── output/                ← empty for now, result saves here
├── models/                ← YOLO downloads model here automatically
├── venv/                  ← virtual environment (auto created)
├── main.py
├── tracker.py
├── requirements.txt
└── README.md