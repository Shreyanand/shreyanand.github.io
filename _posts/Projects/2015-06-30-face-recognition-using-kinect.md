---
title: Face recognition using Kinect
layout: default
tags: tech, Face Recognition, Machine Learning
categories: Projects
main_image: "/images/projects/face_recognition.jpg"
description: Face recognition from an image or a video frame with a depth sensor adds a new flavor to the machine learning problem.
---

## Face recognition using Kinect
[**Project Github**](https://github.com/Shreyanand/KinectFaceRecognition)

Face recognition from an image or a video is an interesting machine learning problem. Augmenting a depth sensor to the input adds a new flavour to the problem. In summer 2015, I interned at [Nayi Disha studios](http://nayidishastudios.com/) to address this challenge. The start-up develops educational Kinect games for primary school children and the face recognition tool helps in tracking the progress of the players. The inbuilt methods of the Kinect SDK required a prior calibration to build a 3d Model of the face, making it ineffective for real-time application with school children. As a proof of concept, I researched and implemented computationally efficient algorithms to address the problem. The first output was a DLL that gave easy access to face training and prediction tools. Then, I developed a demo C# application referencing the designed dll to be used in games designed for over 1000 school children.

The internship was a fun experience and it gave me a glimpse into the startup culture. It was exciting to interact with a small team of experts from research, development, design, and business. It was also my first paid job, and so I enjoyed the fruits of my labor :)
