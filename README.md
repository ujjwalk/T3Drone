# T3Drone
T3 Drone - camera mounted on motor moves as per face movement after identifying the user face

APAC DX Hackathon April 14 and 15, 2016

In this project hack we used a camera + stepper motor + Pi mounted on a drone. 

The Camera is glued to a stepper motor, and connect to raspberry pi via USB. The UWP application running in the background is using native windows 10 face detection API to rotate the stepper motor + camera to center align the detected face.

We used Azure cognitive APIs for face and emotion recognition and then made the camera with motor rotate as per user's face movement
