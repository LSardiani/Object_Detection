# Object_Detection
Project 2 Person Detection 

Hello there!
This project was the second project (Project 2) from IndonesiaAI Computer Vision (CV) Bootcamp Batch 2.

We extracted the COCO 2017 dataset and only used 3000 images with "person" annotations from Roboflow Dataset.

# Background
Object detection and person detection are among the most recent and popular AI features and computer vision technologies. It can be utilised for security and insurance, nursing, health, and production. These recent technologies offer opportunities that can significantly increase customer satisfaction.

Object detection projects have received increased attention in the community of Computer Vision, and there were several models which showed better performance, for example, YOLO and Faster RCNN. 

YOLO (You Only Look Once) is a popular object detection model known for its speed and accuracy. It was first introduced by Joseph Redmon et al. in 2016 and has since undergone several iterations, the latest being YOLOv8.

# Getting started
In this project, we utilised the Roboflow app from the extracted dataset and trained the models (https://roboflow.com/models)

The dataset was downloaded from [https://drive.google.com/drive/folders/19MRsL8ZWR9mXme-bSodyAUHrwIT2Eig7?usp=drive_link](https://universe.roboflow.com/dudrn5704-naver-com/coco2017-3000-person-ver)


# Model
We utilised the YOLOv8 model to perform this project with four different experiments by hyper-tuned the parameters:

Conf = 0.1, 0.2, and 0.25
Epoch = 25 and 50
Image size = 512 and 800

The given sample images illustrate that the higher the conf value the less accurate in detecting the environment beside the "person"

![Screen Shot 2023-08-05 at 14 47 29](https://github.com/LSardiani/Object_Detection/assets/135226112/16df4624-7cfa-454d-bc17-c14d65457a7e)

Experiment 1 vs Experiment 2

![Screen Shot 2023-08-05 at 14 02 12](https://github.com/LSardiani/Object_Detection/assets/135226112/181d6058-7085-4d42-97b3-7e3d2ed186be)


Experiment 3 vs Experiment 4

![Screen Shot 2023-08-05 at 14 02 38](https://github.com/LSardiani/Object_Detection/assets/135226112/e82007a5-66be-4650-9fb0-becc2864151e)


# Results

Training and Validation Curves

Comparison between four models

![Screen Shot 2023-08-05 at 14 03 05](https://github.com/LSardiani/Object_Detection/assets/135226112/d396b04b-eaad-46f7-914c-d4628d2aa161)


# Confusion Matrix

Comparison between four models

![Screen Shot 2023-08-05 at 14 02 55](https://github.com/LSardiani/Object_Detection/assets/135226112/cdd436c9-fc48-4a4e-af5f-d4dd72f2a7e6)


# Actual prediction

![Screen Shot 2023-08-05 at 14 03 31](https://github.com/LSardiani/Object_Detection/assets/135226112/a22f8f43-5b25-4286-a0c9-252e6494a9a8)


Comparison between four models

![Screen Shot 2023-08-05 at 14 03 20](https://github.com/LSardiani/Object_Detection/assets/135226112/8c0edc40-dba4-4493-872c-7395007adf97)


# Deployment 

Comparison between four models

![Screen Shot 2023-08-05 at 14 03 44](https://github.com/LSardiani/Object_Detection/assets/135226112/0a0e4642-5dd3-4d03-bda5-ec572d7cc357)


# Contact
Please reach me my email: lilysilva.dr@gmail.com for any further discussion.

Thank you!
