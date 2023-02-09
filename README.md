# SpiderID_APP
 
# Spider Identification App
Implement YOLO-based models, the state-of-the-art object detection models, as a solution for spider species recognition.
The first version have been trained on Taiwan spiders dataset.

## Overview
Our app uses a YOLO-based Convolutional Neural Network (CNN) trained on open-access data to accurately identify spiders native to Taiwan. With its user-friendly interface, simply upload an image of a spider and the app will return a prediction of its species in real-time. 

## Features
- Real-time spider species identification
- YOLO-based CNN trained on open-access data
- User-friendly interface

## How to use
1. Install the requirements listed in the `requirements.txt` file
```
pip install -r requirements.txt
```
2. Run yolo_download.bat to download yolov7
3. Copy my_detect.py into bin/yolov7, along side with files like detect.py, export.py, etc..
4. Run the app and choose spider image/images for identification
5. Result would be displayed directly if one image was selected, and would be saved in 

## Help protect biodiversity
Join the fight against biodiversity loss and enhance your spider knowledge with our Taiwan Spider Identification App!
