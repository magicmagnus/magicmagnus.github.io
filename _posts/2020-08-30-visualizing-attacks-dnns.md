---
title: Visualizing Adversarial Attacks on DNNs
date: 2020-08-30 00:00:00 -500
categories: [University, Computer Vision]
tags: [Machine Learning, Deep Learning, DNNs, CNNs, Adversarial Attacks, Python, PyTorch]
pin: false
image:
  path: assets/posts/2020-08-30-VCDeerTruck.png
  alt: Visualization of an adversarial attacks on a DNN.
---


For the course "Visual Computing", I have been part of a project to visualize adversarial attacks on Deep Neural Networks (DNNs). The goal of the project was to understand how adversarial attacks work and how they can be visualized. We implemented the Fast Gradient Sign Method (FGSM) and the Projected Gradient Descent (PGD) attack on a pre-trained VGG16 model using PyTorch. We then visualized the adversarial examples and the perturbations added to the original image to create the adversarial example. The project was implemented in Python and the code can be found on [GitHub](