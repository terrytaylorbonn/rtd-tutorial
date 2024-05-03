Part 2 AI HW 
============

xxxxxx:


(first level 2)
---------------

xxxxxx

(second level 2)
----------------

yyyyy



In this part 2 a real CC (companion computer, PI4/Nano) is used (all other components and the world are still simulated).

The goals for the tests in this section include

(1) Fly sim copter (with sim FC),
(2) stand in front of the (real) camera,
(3) the (real) CC recognizes that I am human OR recognizes a guesture and
(4) in response the (real) CC sends a MAVlink flight command to the sim FC (in this example to land the copter).
image

The first 4 sections of this Part B (Gdrive folder) describe how I got a few AI routines (I tried quite a few the first time around) running on the following platform HW:

AIHW1 Ubuntu. Haarcascades and mediapipe gestures running on the Ubuntu (documents 2_B1.1,2,3, 23.0122-0131). I started using Ubuntu as the first test platform (instead of PI4/Nano) to avoid issues (such as camera drivers; PI4/Nano used their custom version of 18.04 Ubuntu).


AIHW2 PI4. Haarcascades, TF-lite, and mediapipe face meshes (document 2_B2, 23.0119-0121).


AIHW3 Nvidia. OpenCV, haarcascades (documents 2_B3_2a-1, 2_B3_3a, 23.0110-0118; 2_B3_2a describes Nvidia tutorials, for which I had trouble getting the camera other drivers setup).

AIHW4 STM. Covers AI implmentations on STM hardware.

The last section covers:

AI research. This section includes mainly the hands-on demos I did when I first started out studying AI.

