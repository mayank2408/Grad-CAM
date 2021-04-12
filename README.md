# Grad-CAM
Ecplaining decisions of neural networks is an active area of research. Grad-CAM is a very popular tool that is used to analyse results of CNN model for classification tasks. 
1. In this work, we apply Grad-CAM for videos using following approaches:
  - We divide the video samples into equally spaced image frames which gets processed through different models
  - First model is ResNet 3D which uses 3D convolution over space and time.
  - Second model consists of vanilla LSTM over 2D CNN
  - Third model uses LSTM over 2D CNN model with attention.

2. We also propose a method for using Grad-CAM for regression. We show our results on Visual Odometry task which is an image based regression task.
