# Mall-Crowd-Counting-Challenge
![Mall Crowd Counting Challenge](https://v-count.com/wp-content/uploads/2020/01/blog-jan4.png)   
<hr>  

## Challenge Details

***Problem Statement***  

The use case is as such : That you are given a task to count the number of people in a shopping mall

***Problem Dimensions***

This problem has following dimensions

Use triangulation or any other algorithm to count number of people in a shopping mall.
State the margin of error or confidence interval of the output.
Since the count of people is a function of time, solution should be such that it takes continuous video feed and give count of people.
IE.g.In a shopping mall with 5 adjacent shops, can the solution give count of people in each shop and aggregate it at the mall level in a live scenario where there is a continuous camera feed in each shop and the corridor.
State assumptions used.

***Team Name- CCC5_SOA***
<hr>

## Problem Solving Approach:
For the above problem statement we had deviced three ways to 


## Technological Specification:  

**1. People Counting System for Shopping Malls:**  
**Language:** Python.   
**Frameworks Used**: Opencv, pytorch, imutils, dlib, argparse.   
**Pretrained Model for Object Detection algorithm:** YOLO MobileNet SSD.   
**Object Tracking Algorithm**: Centroid Tracker(MOSSE Algorithm).

**2. People Counter in Crowded Malls:**  
**Language:** Python.   
**Frameworks Used**: torch-vision, pytorch, cv2, matplotlib, argparse.     
**DataSet Used:** VGG 16 v3   
**Pretrained Model used for transfer learning:** VGG 16 v3 SSD

## Project Implementation:

**1. People Counting System for Shopping Malls:** [https://github.com/Zeo-shark/People-Counting-System-for-Shopping-Malls](https://github.com/Zeo-shark/People-Counting-System-for-Shopping-Malls).   
 
 - ***Data-Flow Diagram :***
   
![./src/People_Counting1.PNG](./src/People_Counting1.PNG)  

- ***Output fpr People Counter System:*** 

output_video_crowd.mp4 file  

 ![https://imgur.com/tZYiOkt.gif](https://imgur.com/tZYiOkt.gif) 
 
  Log files for output_video_crowd.mp4 : 

 ![https://imgur.com/CV2nCjx.png](https://imgur.com/CV2nCjx.png)

**2. People Couter in Crowded Mall:** [https://github.com/Zeo-shark/People-Counter-in-Crowded-Mall](https://github.com/Zeo-shark/People-Counter-in-Crowded-Mall).  

- ***Data-Flow Diagram :***

![./src/Crowd_Counter_system.PNG](./src/Crowd_Counter_system.PNG)   

 - ***Output for People Couter in Crowded Mall:***  

 ![https://www.xpandretail.com/wp-content/uploads/2018/01/customers-counting-system.jpg](https://www.xpandretail.com/wp-content/uploads/2018/01/customers-counting-system.jpg) output_1.png

<hr>  
 
 ## Use-Cases  
 
 Primarily we are focusing on the use of this Crowd Counting System in Shopping Malls. as shown below :
 1. At every entrance or exit a camera will be placed to count the number of people entering or leaving the premises.
 ![People_Counting](https://www.mobotix.com/sites/default/files/styles/facebook/public/2020-06/backontrack_1_930x550.jpg?h=c4a9cdb7&itok=p09sYf8W).

 2. The Concourse, the hallway, the pathsways through the mall will be divided into different zones and each zone will have an IP Camera to perform head-count on the real-time video stream.
 ![Crowd_Counting](https://global.canon/en/technology/img/frontier/count2019_img1.jpg) 

**These above can be represented as :**

 ![./src/Crwd_Counting_Mall.PNG](./src/Crwd_Counting_Mall.PNG)


 ## References:

 1. [https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/](https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/) by Adrian Rosebrock


 2. https://www.researchgate.net/publication/236292403_Real-time_Crowd_Monitoring_using_Infrared_Thermal_Video_Sequences