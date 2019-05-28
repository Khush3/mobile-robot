# Pose Estimation of a differential drive robot using Odometry

# Overview
A teleop-controlled robot which can estimate it's position (abscissa and ordinate), and orientation(angle) in a 2-D space.
Data received from encoders is processed on raspberry-pi using ROS. Complete processes is executed via three nodes
position-estimation-node, encoder-node, teleop-motor-control-node.
positon-estimation-node subscribes to encoder-node and teleop-motor-control-node and prints localization data.
teleop-motor-control-node control node controls robot using realtime keyboard control.
encoder-node reads sensor values and publishes message when counters increment.

# Sample


# Team Members:
1.Khush Agrawal

2.Abhay Khandelwal

3.Shreyash Sonawane

4.Ameya Talatule

# Team Mentors:
1.Akshay Kulkarni

2.Sagar Swami
