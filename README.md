# YOLO
source: https://dipankarmedh1.medium.com/real-time-object-detection-with-yolo-and-webcam-enhancing-your-computer-vision-skills-861b97c78993
Real Time Object Detection using YOLO


To Set up the environment: Install all the necessary dependencies, such as ultralytics, opencv-python.
$ pip install opencv-python
$ pip install ultralytics
from ultralytics import YOLO
model = YOLO("yolo-Weights/yolov8n.pt")
