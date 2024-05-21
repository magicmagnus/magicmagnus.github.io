---
title: Traffic Light Detection
date: 2024-03-15 00:00:00 -500
categories: [University, Computer Vision]
tags: [Machine Learning, Deep Learning, CNNs, Python, PyTorch]
pin: false
image:
  path: assets/posts/final_prediction.png
  alt: Results of the Traffic Light Detection model on a batch of images.
---


For the course "Bildverarbeitung, Maschinelles Lernen und Computer Vision", I have been part of a project to detect traffic lights in images and videos as well as the state of the traffic light (red, red-yellow, yellow, green, off), to be used in driver-assistance systems and autonomous vehicles. 

We split our pipeline into multiple separate steps, my contribution to the project was the implementation of the traffic light State Detection model using a custom ResNet architecture, implemented in PyTorch. The model was trained on our self-annotated data from the [DTLD datset provided by driveU](https://www.uni-ulm.de/in/iui-drive-u/projekte/driveu-traffic-light-dataset/). The final model achieved an accuracy of 97.7% on the test set.