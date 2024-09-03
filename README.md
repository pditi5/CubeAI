# CubeAI
AI-powered object detection for construction cubes, assessing usability based on smoothness and cracks to ensure quality and safety on job sites.
![image](https://github.com/user-attachments/assets/35b7de88-0118-41cc-9dcf-2022930d9535)

 
## Object Detection and Cropping of Cubes Using YOLOv10
## Project Overview

This project implements an object detection pipeline using the YOLOv10 model to identify and crop images of cube objects from a dataset. The workflow includes dataset organization, model training, evaluation, and cropping of detected objects.

## Features

- **Dataset Organization**: Automatically organizes images and labels into training, validation, and test sets.
- **Model Training**: Trains the YOLOv10 model on the provided dataset.
- **Performance Evaluation**: Calculates precision, recall, and F1-score to evaluate model performance.
- **Object Cropping**: Crops detect cube objects from images and save them to a specified directory.

## Requirements

- Python 3.x
- `ultralytics`
- `opencv-python`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `tqdm`

## Installation

Install the required packages using pip:

```bash
pip install ultralytics opencv-python numpy matplotlib scikit-learn tqdm
