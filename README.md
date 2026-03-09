AI Object Detection Assignment
Author: Paballo Bogacwi

Name: Paballo Bogacwi
Student Number: 52442179
Module: Artificial Intelligence
Institution: North-West University

1. Introduction

Artificial Intelligence has made it possible for computers to analyse images and understand what is happening inside them. 
One of the most common applications of this technology is object detection, which allows a computer to recognise and locate objects in images or video.
In this assignment, we implemented a basic AI object detection system using Python and computer vision libraries. 
The program processes a video stream and identifies objects such as people, cars, and everyday items.
Once detected, the system draws boxes around the objects and labels them on the screen.
Through this project, we were able to explore how AI models can be applied to real-world problems involving visual data.

2. Objective of the Assignment

The main goal of this project was to:
Understand the concept of object detection in artificial intelligence
Use Python and OpenCV to process visual data
Implement a program that detects objects in real time
Work with pre-trained AI models rather than training a model from scratch
By completing this assignment, we gained practical experience working with computer vision tools and AI-based systems.

3. Tools and Technologies Used

For this project, we used the following technologies.
Programming Language : Python 3.14
Libraries
OpenCV – used for image and video processing
NumPy – used for numerical operations
These tools allowed us to analyse images frame by frame and apply an object detection model to identify objects in real time.

4. Program Structure

The project folder contains the following important files:
AI_Object_Detection
│
├── lab_1.py
├── coco.names
├── yolov3.cfg
├── yolov3.weights
└── README.md


5. How the System Works

The object detection program follows several steps:
We first load the pre-trained object detection model.
A video stream is captured from the webcam or a video file.
Each frame from the video is processed individually.
The AI model analyses the frame to detect objects.
When an object is detected, a bounding box is drawn around it.
The name of the object and a confidence score are displayed on the screen.
This process continues repeatedly while the program is running.

6. Installation and Setup

Before running the program, we must install the required Python libraries.
Open the Command Prompt and run the following command:
pip install opencv-python numpy
After installing the libraries, ensure that all the project files are stored in the same folder.

7. Running the Program

To run the object detection program:

Open the Command Prompt
Navigate to the project folder
Run the following command:
python lab_1.py
Once the program starts, a window will appear displaying the video feed. The system will highlight detected objects with boxes and labels.
Press Q to exit the program.

8. Example Output

When the system detects objects, it highlights them using a rectangle and displays the object name along with a confidence score.
Examples of objects that may be detected include:
Person
Car
Truck
Phone
Chair
Bottle
The detection results appear directly on the video stream in real time.

9. Challenges Encountered

During the development of this project, we encountered several challenges, including:
Installing the required Python libraries correctly
Configuring the object detection model files
Ensuring the webcam or video input worked properly
Managing the speed of real-time detection
These issues were resolved through testing and troubleshooting different configurations.

10. Conclusion

This assignment allowed us to gain practical experience in applying artificial intelligence techniques to visual data.
By using Python and OpenCV, we were able to implement a functional object detection system capable of identifying objects in real time.
Overall, the project demonstrates how AI and computer vision can work together to build intelligent systems that interpret and analyse visual information.










Ensuring the webcam or video input worked properly
Managing the speed of real-time detection
These issues were resolved through testing and troubleshooting different configurations.
