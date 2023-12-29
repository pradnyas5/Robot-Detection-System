# Robot-Detection-System
A "Pose-Estimation" project was implemented using fiducial markers and YoloV5 object detection. 
The project was called "Project Dexter" and was associated with Technodune Pvt. Ltd.
Please find the technical intricacies of the project in the report named, "ProjectDexter.pdf" provided above.

Following is the demonstration of the objectives achieved in the setting of the project:

## 1. Robot detection using Fiducial Markers
   
   Each robot was marked with a fiducial marker and hence carried a unique identification number.
   
   The camera would process the input video into a stream of frames. Each frame had a distortion and to ensure minimal data loss, perspective transformation and smoothening was implemented. 
   The input frame was then corrected for its perspective and a straightened camera image was obtained.

   ![PT_Frame1](https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/0a4a0d8d-c66d-41bf-ba2b-9efd3fb353ce)   
   *Distorted Image*

   ![PT_Frame2](https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/597b092b-a84c-4474-96c8-886e2d0077c2)   
   *Straightened Image*   
      
   ![SAVE](https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/9da9965e-40d7-4489-b367-8e737588e4ec)   
   *Robot Pose Estimation*

## 2. Robot detection using YoloV5
   
   Implemented "Transfer Learning" to train a model using YoloV5.

   Achieved an accuracy of 85-90 % in Robot detection.
   
   ![RD_1](https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/31f48f02-e775-4082-90b8-4850eef258a8)
      
   ![RD_2](https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/0e2c2363-8f45-4ba7-9e2b-d6842fb9b9e8)

## 3. Robot Motion

   The robot kinematics for the holonomic motion were implemented using C language. The controller responsible for the control of robot movement was ESP32S. Following is a glimpse of Robot movement:

   https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/ac979192-d204-410c-ac2a-0f6174018360


   
