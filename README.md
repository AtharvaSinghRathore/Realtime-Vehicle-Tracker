# Vehicle Tracking using YOLO and SORT
This project demonstrates a vehicle tracking system implemented using object detection and online tracking algorithms. It utilizes the YOLO (You Only Look Once) object detection model to identify vehicles in video frames and then tracks their movements across frames using the SORT (Simple Online and Realtime Tracking) algorithm.
## Features
- Detects vehicles including cars, trucks, buses, and motorbikes in video frames.
- Tracks the detected vehicles over time using the SORT algorithm.
- Displays tracking information, bounding boxes, and vehicle counts on the video frames.
## Prerequisites
- Python (3.x recommended)
- OpenCV
- NumPy
- Ultralytics YOLO (YOLO model weights)
- SORT (Simple Online and Realtime Tracking)
- Video file for tracking (e.g., "cars.mp4")

  ## Installation
  1. Clone this repository:
      - git clone https://github.com/AtharvaSinghRathore/vehicle-tracking.git
      - cd vehicle-tracking
  2. Install required Python packages:
   - pip install -r requirements.txt
  3. Download YOLO model weights (e.g., yolov8l.pt) and place them in the Yolo-Weights directory.

## Usage
1. Replace the paths to your video file and mask images in the Car-Counter.py script.
2. Run the script:
- python Car-Counter.py
3. The processed video with tracking information will be displayed.

## Notes
- Make sure to adjust detection thresholds and parameters based on your specific use case.
- The provided implementation focuses on vehicle tracking but can be extended for other objects.
   
    
