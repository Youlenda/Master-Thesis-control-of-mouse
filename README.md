# Master-Thesis-control-of-mouse

Abstract

A long time ago, the human being was always dreaming about picking things up, taking a simple hand gesture. Although up to now, no one could've moved things without having direct touch, Artificial Intelligence allows individuals to control the intelligent system by using hand gestures in front of a camera and without having a single contact.
In the proposed thesis, a user interface is designed to establish an interaction between humans and computers, so the pointer can be controlled using users' hand gestures. The hand gestures' frames are captured and processed through a webcam and using techniques, libraries, and functions of image processing. Afterward, the hand location is detected by neural network algorithms.
In order to control the computer's cursor using hand gestures, a hand dataset is collected, which has 6720 image samples, including 4 classes which are fists, palms, pointing to the left, and pointing to the right. The images of the dataset are captured by 15 persons in simple backgrounds and different light conditions.
The collected dataset trains a convolutional neural network based on EfficientNet-B0 and fully-connected layers. The trained network is saved for two proposes: first, to classify the output frames of the hand detector and predict a label for each frame; Second, to compare the output frames with the images of the dataset.
Eventually, the predicted label converts to command for controlling the cursor. The defined commands are turning the mouse on or off, moving the cursor, left and right-clicking. Accuracy of the presented mouse reaches to 92.6 percent and is appropriate to use in different backgrounds. Also, Python programming language is used in order to design the presented mouse.

keywords: Hand Gesture Recognition, Dataset, Convolutional Neural Network, Classification, Computer Mouse, and Object Detection
