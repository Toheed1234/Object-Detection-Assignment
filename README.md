# Object-Detection-Assignment

This repository contains the solution for assignment of the Deep Network Development course. The task involves implementing a custom object detection model using PyTorch and fine-tuning an existing object detection model (YOLOv8) on a synthetic dataset.

The goal of this project is to compare the performance of a custom-built Convolutional Neural Network (CNN) model and the YOLO model on detecting one of three objects: Frog, Man, or Teddy. This assignment is a simplified object detection task where each image contains only one object.

Network: Custom Object Detection
Objects: Frog, Man, Teddy
Task Description
The main goal of the assignment is to:

Generate a synthetic dataset containing images with only one object from the classes: Frog, Man, or Teddy.
Train a custom CNN-based object detection model using PyTorch.
Fine-tune a pre-trained YOLOv8 object detection model on the same dataset.
Compare the performance of both models using metrics such as loss, precision, recall, and mean average precision (mAP).
Visualize the training progress with graphs of loss, accuracy, and predictions.
Implement regularization techniques like dropout, batch normalization, and early stopping to avoid overfitting.
The dataset is used to train the models, and the metrics should show results better than random guessing. The loss should decrease throughout the epochs.

Dataset
This project uses a synthetic dataset of three objects:

Frog
Man
Teddy
Each image contains one object, and the corresponding bounding box is labeled for object detection training.

Dataset Details:
The dataset is synthetically generated, containing images with objects placed in various positions.
The annotations include the object class and the bounding box coordinates.
You can find a sample of the data in the repository.
