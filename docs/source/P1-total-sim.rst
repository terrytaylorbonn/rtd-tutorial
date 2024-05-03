Part 1 Total simulation 
=======================

Total simulation is a simulation where all components are simulated. This includes the world, the flight computer, the ground control station, the companion computer, and the camera + AI algorithms.

docs/source/images/airplane_person.png


This kind of simulation is valuable because it allows to test the whole system in a controlled environment. It is also useful to test the system in extreme conditions that are difficult to reproduce in real life.

The flight computer (FC) controls all surfaces (which are just the rotors). Simple Mavlink commands are sent to FC to fly the copter. Therefore copter reaction to flight commands can be simulated accurately.
Ground control stations (QGC, MP) are computer based anyway.

The CC (companion computer) runs several protocols (ROS, MAVROS, MAVLINK, MAVPROXY) that can be simulated accurately.



