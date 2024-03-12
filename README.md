# Distance Measurer with Webcam

## Overview
This project is a Python application that uses computer vision techniques to measure the distance of objects from a webcam. It utilizes the YOLOv8 object detection model and OpenCV library for real-time object tracking and distance calculation.

## Features
- Real-time distance measurement using webcam feed.
- Object detection with YOLOv8.
- Display of distance measurements on the video feed.

## Requirements
To run this project, you'll need the following installed on your system:
- Python 3.8 or later
- OpenCV-Python
- Ultralytics YOLO library

## Installation
1. Navigate to the directory where you want to clone the repository:
```bash
cd /path/to/desired/directory
```

2. Clone this repository:
```bash
git clone https://github.com/Op27/distant-measurer-webcam.git
```

3. Change to the project directory:
```bash
cd distant-measurer-webcam
```

4. Install the required Python packages:
```bash
pip install opencv-python ultralytics
```

## Usage
1. Make sure that your webcam is functioning.
2. To start the distance measurer, run the following command in your terminal:
```bash
python app.py
```
3. The application will open a window displaying the webcam feed with bounding boxes around detected objects and their estimated distances.
4. Press 'q' to quit the application.
5. The application will save the recording as an "output.avi" file in the project directory.   



## Configuration
- The `pixel_per_meter` variable in the script can be adjusted to calibrate the distance measurement based on your camera's specifications.
- The `yolov8s.pt` file contains the pre-trained YOLOv8 model weights. You can replace it with a different model if desired.  


## Contributing  
Contributions to improve Distant Measurer via Webcam are welcome. Please feel free to fork the repository and submit pull requests.  


## License
This project is licensed under the [MIT License](LICENSE).  



## Acknowledgements
I would like to express my gratitude to the Ultralytics team for the YOLOv8 model and utilities.

- The [Ultralytics](https://github.com/ultralytics) team for developing the powerful YOLOv8 object detection model, which serves as the foundation of our distance measurement application.
- The [OpenCV](https://opencv.org/) community for creating and maintaining the robust computer vision library utilized in this project.