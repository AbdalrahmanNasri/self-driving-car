
# self-driving-car

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




## results

the given flowchart demonstrates the algorithm 

![Picture1](https://github.com/user-attachments/assets/233d94d8-10ce-473d-88e1-6901e03846ac)

point cloud images and bird's eye view:

![1](https://github.com/user-attachments/assets/5ae11483-21b6-45ed-bcc1-b83ba05583af)
![2](https://github.com/user-attachments/assets/1089a2eb-5652-48cc-a908-56333a99e064)
![3](https://github.com/user-attachments/assets/7c658199-35ad-43e7-8821-aa4d205e069b)

detection and labels:

![4](https://github.com/user-attachments/assets/d1e41705-f1db-4a13-9558-f61a4c150d8f)
![5](https://github.com/user-attachments/assets/dd500158-a3e5-4eed-8354-c19da3c05620)
![image](https://github.com/user-attachments/assets/a3f889f5-554d-4434-aef8-218d33e31c03)


tracking loss:

![6](https://github.com/user-attachments/assets/e6072717-3cd0-4cc3-baa0-d2439fde35eb)

## full output video
you can watch the full output video from the link below.
https://youtu.be/6PGqd4melTQ?si=QXeI6COKTYDNuQf5


