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

The dataset was downloaded from (https://app.roboflow.com/adalovelace/cocopersondetection/versions)


# Model
We utilised the YOLOv8 model to perform this project with four different experiments by hyper-tuned the parameters:

Conf = 0.1, 0.2, and 0.25

Epoch = 25 and 50

Image size = 512 and 800

The given sample images illustrate that the higher the conf value the less accurate in detecting the environment beside the "person"

![Screen Shot 2023-08-05 at 21 05 02](https://github.com/LSardiani/Object_Detection/assets/135226112/e0e7744e-32c3-41b8-a759-f3ef2ca53fa8)


Experiment 1 vs Experiment 2

![Screen Shot 2023-08-05 at 21 05 11](https://github.com/LSardiani/Object_Detection/assets/135226112/a7b3e5f8-b2e2-41dc-af78-d6ee6e4c934b)



Experiment 3 vs Experiment 4

![Screen Shot 2023-08-05 at 21 04 52](https://github.com/LSardiani/Object_Detection/assets/135226112/a8b97093-49ce-4ab7-b11a-290f3c46bfe7)



# Results

Training and Validation Curves

Comparison between four models

![Screen Shot 2023-08-05 at 21 04 23](https://github.com/LSardiani/Object_Detection/assets/135226112/222db1e7-cd97-40d5-89e8-7d1fafe647a3)



# Confusion Matrix

Comparison between four models

![Screen Shot 2023-08-05 at 21 04 39](https://github.com/LSardiani/Object_Detection/assets/135226112/e22500c4-ee55-4012-bc85-0dafb399c467)



# Actual prediction

![Screen Shot 2023-08-05 at 21 04 06](https://github.com/LSardiani/Object_Detection/assets/135226112/07e3a2ef-32bd-4c3b-8b44-c251fb9a2b38)



Comparison between four models

![Screen Shot 2023-08-05 at 21 04 14](https://github.com/LSardiani/Object_Detection/assets/135226112/cf9f3a08-5d90-40d9-a0d5-2c418ff58260)



# Deployment 

Comparison between four models

![Screen Shot 2023-08-05 at 21 03 50](https://github.com/LSardiani/Object_Detection/assets/135226112/e0985ee8-cd88-4814-be5f-38d2d9a21af3)


It can be concluded that: the lower the image size, it can be predicted more accurate person in crowded (more than one person) images.

# Summary for the four models:

![Screen Shot 2023-08-05 at 21 03 37](https://github.com/LSardiani/Object_Detection/assets/135226112/bba80eec-960d-40b5-b704-e49e85028b86)



# Contact
Please reach me by email: lilysilva.dr@gmail.com for any further discussion.

Thank you!
