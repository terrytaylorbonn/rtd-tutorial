Part 2 AI HW 
============

In this part 2 a real CC (companion computer, PI4/Nano) is used (all other components and the world are still simulated).

Goals
---------------

The goals for the tests in this section include

(1) Fly sim copter (with sim FC)
(2) Stand in front of the (real) camera
(3) The (real) CC recognizes that I am human OR recognizes a guesture 
(4) In response the (real) CC sends a MAVlink flight command to the sim FC (in this example to land the copter)

HW/AI combinations used
-----------------

- Ubuntu. Haarcascades and mediapipe gestures running on the Ubuntu . I started using Ubuntu as the first test platform (instead of PI4/Nano) to avoid issues (such as camera drivers; PI4/Nano used their custom version of 18.04 Ubuntu).

- PI4. Haarcascades, TF-lite, and mediapipe face meshes.


- Nvidia. OpenCV, haarcascades.

- STM. Covers AI implmentations on STM hardware.

General AI research
-----------------

This part also includes the many hands-on demos I did when I first started out studying AI.

