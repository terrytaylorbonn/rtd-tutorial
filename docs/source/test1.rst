test1
=====


You start to understand what AI really is when you start using it. And this Wiki shows you step-by-step how to do that for various types of object detection/recognition AI (and some other types, such as gesture recognition).

And you can realistically use AI on a drone thanks to
  - Very powerful AI circuits customized for specified functions with **low power**
  - Software tools are making AI accessible to non-experts
  - Cost has drastically decreased

The copter AI for this project focuses mainly on object recognition. The CC (companion computer)
  - Is the ROS messaging host (master).
  - Receives input from the camera via ROS messages (or a direct connection to the camera without ROS).
  - Runs an AI routine to detect or recognize object. 

