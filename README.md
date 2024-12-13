Truck Detection Using YOLOv8
This repository contains a project for detecting trucks in images using the YOLOv8 (You Only Look Once) object detection model. The project involves training the YOLOv8 model on a custom dataset, evaluating its performance, and making predictions on test images. YOLOv8 provides a state-of-the-art approach for object detection tasks with high accuracy and speed.

Features
Custom Dataset Training: Trains YOLOv8 on a dataset specifically designed for truck detection.
Model Evaluation: Validates the model's performance on unseen data with visualization of predictions and labels.
Real-Time Detection: Applies the trained model to test images and outputs predictions.
Visualization: Uses visual tools to display training progress, validation results, and detection outcomes.
Workflow
Mount Google Drive: Integrates with Google Drive to access datasets and save models.
Install Dependencies: Installs the required libraries, including YOLOv8 and Pillow for image processing.
Training:
Trains YOLOv8 on the custom truck detection dataset.
Configured for 50 epochs with 640x640 input image size.
Generates plots of training progress and saves the best-performing model weights.
Validation:
Evaluates the trained model on validation data.
Generates images with bounding boxes showcasing predictions.
Prediction:
Applies the trained model to a test dataset.
Detects trucks with a configurable confidence threshold and saves the output images.
Requirements
Python 3.7+
Google Colab (optional for cloud-based training)
Libraries: ultralytics, Pillow
