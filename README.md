# Robot-Detection-System
A "Pose-Estimation" project implemented using fiducial markers and YoloV5 object detection. 
The project was called "Project Dexter" and was associated with Technodune Pvt. Ltd.
The task alloted was to detect a swarm of omni-wheeled robots and estimate their pose with respect to each other as well as with respect to the camera frame. This was done in following ways:

1. Robot detection using Fiducial Markers
   > Each robot was marked with a fiducial marker and hence carried an unique identification number.
   > The camera would process the input video into a stream of frames. Each frame had a distortion and to ensure minimal data loss, perspective transformation and smoothening was implemented. The         input frame was then corrected for its perspective and a straightened camera image was obtained.

      ![PT_Frame1](https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/0a4a0d8d-c66d-41bf-ba2b-9efd3fb353ce)
      
      Distorted Image

      ![PT_Frame2](https://github.com/pradnyas5/Robot-Detection-System/assets/93536494/597b092b-a84c-4474-96c8-886e2d0077c2)
      
      Straightened Image

