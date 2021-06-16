# udacity-2D-robot-motion
Keep track of a vehicle's  𝑥  and  𝑦  coordinates as it moves in any direction. Udacity - Intro to Self-Driving Cars - Chapter:8 - Lesson:3
# Initialization
The constructor (__init__) of class Vehicle sets (x,y) = 0.0 m, heading = 0.0 rad, and history to [].
# Working Algorithm - Main
drive_forward() method updates (x,y) tulip according to displacement (that is a function argument) and current heading. dx is easily calculated with displacement x cos(theta). Theta is the heading angle in radians. Same for dy. Before updating the (x,y) values, they are appended to history (a list of tuples), in order to keep the past trajectory. Then (x,y) values are updated.
set_heading() method just converts the heading unit from degrees to radians.
turn() takes in angle_in_degrees as an argument. First, this is converted to radians. Then heading is updated accordingly.
show_trajectory() method plots the (x,y) values in the history.
# Testing Code
Next cells in the jupyter notebook contains testing codes.
