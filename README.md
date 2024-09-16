# MappingDrone-LocatingDroneInAxes
The Real-Time Drone Odometry leverages Computer Vision to track and calculate the drone’s position, orientation, and movement in space. Odometry, a method used to estimate a moving object’s change in position over time Here, the drone’s position is estimated by combining its linear velocity (movement along X and Y axes) with its angular velocity (changes in yaw). Each time the drone moves, the new position is calculated using trigonometry based on the direction it’s facing and how far it moves. This forms the basis of odometry, which tracks the cumulative displacement of the drone over time. The system continuously updates and plots the drone’s current position on a 2D grid, providing a visual representation of its real-time path. This approach to drone odometry is fundamental in enabling the drone to navigate autonomously or follow specific paths, and it’s useful for mapping and navigation tasks.
