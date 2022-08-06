# Game_automation
Basically we divide the project into two module, One which controls the keyboard using ctypes library and the other main code which would take live feed from the webcam and detect the hand pose. Here we will control the car game with our hand gestures and the technique used is Mediapipe hand estimator. Mediapipe hands uses ML pipelines consisiting of multiple models working together. This will detect our hand fold using palm detection model after that hand landmark model performs precise keypoints localization.
So, we aim to design a model enforcing the concept of “OpenCV and Media Pipe
Hands in Python and control the game interface with our hand gestures” which is
a very cool and new way to interact with the system.

MediaPipe offers ready-to-use yet customizable Python solutions as a prebuilt Python package.
Mediapipe library as mp has been imported from the python library.
In this project, we use media pipe python library to detect hand landmarks. We will be using a
drawing styles model from media pipe solutions to detect hand landmarks. We also saw how we
can access different landmarks of the hands which can be used for different computer vision
applications such as sign language detection, gaming etc.
Required Libraries
Mediapipe is a cross-platform library developed by Google that provides amazing ready-to-use ML
solutions for computer vision tasks.
OpenCV library in python is a computer vision library that is widely used for image analysis, image
processing, detection, recognition, etc.
Directkeys it is a module called within the main function. Which controls the keyboard mapping to
the hand gestures.
1: Import all the necessary libraries, In our case only two libraries are required.
2: Initializing darwing styles model and Drawing utils for detecting and drawing landmarks on the
image.
