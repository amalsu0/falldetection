# Fall Detection

## Project Overview
Motivated by the growing demand for solutions that improve safety, this project aims to address the problem of delayed medical attention by detecting falls and possible risks quickly. The image dataset contains various scenarios of falls occurring in different settings and environments. 
The solution could be used to help several domains, including: 
 • Elderly care homes
 • High-risk workplaces like construction sites.
 • Public spaces such as parks, streets, or shopping centres. 

## Dataset Description
The dataset consists of images of falling people in different environments and scenarios. There is one class called (Fall-Detected) and the dataset doesn’t contain any background images. As it is an object detection problem, the labels consist of the bounding box boundaries of the object in yolov8 format. The dataset is randomly divided into 88% Training Set, 8% Validation Set, and 4% Testing Set.

## Implementation
This project used the state-of-the-art (SOTA) model in object detection Yolov8 which is the latest version of You Only Look Once (YOLO) family. Yolov8 is built on cutting-edge advancements in deep learning and computer vision, offering unparalleled performance in terms of speed and accuracy.

## Dependencies
- Ultralytics, a Python interface that allows to quickly implement the object detection model yolov8.
- roboflow, to download the dataset in yolov8 format.

## File Descriptions
- FallDetection.ipynb: the main folder that build the model, download the dataset, and train the model
- best.pt: the output model.
- results: the results for every epochs
