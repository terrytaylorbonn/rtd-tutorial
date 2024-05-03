Part 1 Total simulation 
=======================

Total simulation is a simulation where all components are simulated. This includes the world, the flight computer, the ground control station, the companion computer, and the camera + AI algorithms.

![ai-person-plane](images/airplane_person.png)

Note: I got my start with total simulation thanks to an incredible [video series put together by Eric from Intelligent Quads](https://www.youtube.com/playlist?list=PLy9nLDKxDN683GqAiJ4IVLquYBod_2oA6) 4 years ago. I could not have made such fast progress without his series. His was the only (genuinely) step-by-step intro to the drone world that I found (my version of his series is more up-to-date and easier to follow).

This kind of simulation is valuable because it allows to test the whole system in a controlled environment. It is also useful to test the system in extreme conditions that are difficult to reproduce in real life.

The flight computer (FC) controls all surfaces (which are just the rotors). Simple Mavlink commands are sent to FC to fly the copter. Therefore copter reaction to flight commands can be simulated accurately.
Ground control stations (QGC, MP) are computer based anyway.

The CC (companion computer) runs several protocols (ROS, MAVROS, MAVLINK, MAVPROXY) that can be simulated accurately.



