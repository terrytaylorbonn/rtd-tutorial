Part 5 Other topics 
==================

These are topics that are perhaps not directly a part of the drone build, but you might need to know. This list includes only those topics I have done examples for (this list should grow in the future).


1 ROS
-----

This is the unintelligible blurb that you get from the ROS website: "ROS is a middleware for robotics. It is a collection of tools, libraries, and conventions that aim to simplify the task of creating complex and robust robot behavior across a wide variety of robotic platforms." 

This is how I would explain ROS:
- ROS Core: This would be the CC (companion computer) that receives and sends messages from ROS nodes.
- ROS Nodes: This would be any components that want to share messages. For example, a camera and lidar could be ROS nodes IF they have the internal processor that can implement a node.

Why is this important (a question I am not sure the ROS docs ever clearly answer)? This makes it possible for the camera and the lidar to be auto-discovered and auto-configured to talk to the CC. No more endless hours trying to install and configure camera/lidar drivers.


2 Wired
-------

I spent about a month researching how to configure stealty (over a wire, not wireless) communication between the drone and the pilot / ground station. Camera video is fairly simple to do, but getting RC or joystick inputs to the drone over a wire is not. This little project has been put on hold for now.


3 STM32
--------

STM is a company that makes microcontrollers. The STM32 is a series of microcontrollers that are used in many drones. I have done a few examples of how to program the STM32 microcontroller using STM tools (this is sometimes very convenient). STM products and documentation are of really high quality (unlike the Chinese brand components).



