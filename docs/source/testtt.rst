ttttttttttttttttttttt
===================================


You start to understand what AI really is when you start using it. And this Wiki shows you step-by-step how to do that for various types of object detection/recognition AI (and some other types, such as gesture recognition).

And you can realistically use AI on a drone thanks to
  - Very powerful AI circuits customized for specified functions with **low power**
  - Software tools are making AI accessible to non-experts
  - Cost has drastically decreased

The copter AI for this project focuses mainly on object recognition. The CC (companion computer)
  - Is the ROS messaging host (master).
  - Receives input from the camera via ROS messages (or a direct connection to the camera without ROS).
  - Runs an AI routine to detect or recognize object. 

  ![image](https://github.com/terrytaylorbonn/auxdrone/assets/20533814/e8bb1a0d-a40c-4443-85f1-3c83634354f4)

The following diagrams shows where the CC fits in the drone physically and functionally ("flight board" = CC). The second diagram is from Intelligent Quads.

![image](https://github.com/terrytaylorbonn/auxdrone/assets/20533814/a1ab00d8-4f72-4445-a64d-fbaf6f3c64f9)

![image](https://github.com/terrytaylorbonn/auxdrone/assets/20533814/7d3169c1-1ccb-40cc-9591-5681fd45652c)
