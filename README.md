
# Project Title

This project is an algorithm of object detection and tracking for self driving car by sensor fusing and extended kalman filter implementation

. It is required to fuse LIDAR and camera measurements, then track vehicles overtime. The data used in this project are from the Waymo open dataset. 
Object detection will be done using pre-trained models. An extended Kalman
filter will be applied for sensor fusion and tracking.


## Setup: 

1. The project has been written in python 3.10.8, please make sure you have the latest 
python version.

2. Before running the project, some libraries must be installed. The required libraries are mentioned in the requirement.txt file. 

3. Download the Waymo open dataset reader toolbox. The Waymo open dataset reader will help reading the dataset, it is light and does the job. It can be downloaded from many sources, for example, you can download it from https://waymo.com/open/ 
6. After downloading the dataset, copy the sequences into the folder “dataset”. 

7. The object detection is done using two pre-trained models. Download darknet model and the fpn_resnet model. Copy the weights into 
/tools/objdet_models/darknet/pretrained and 
/tools/objdet_models/fpn_resnet/pretrained, respectively. 




