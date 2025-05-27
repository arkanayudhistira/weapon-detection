# Implementing YOLO11 for Real-time Weapon Detection

## Overview

This project demonstrates a real-time weapon detection system using the YOLO (You Only Look Once) object detection algorithm. Leveraging the power of YOLO11, the notebook guides users through dataset preparation, model training, validation, and inference stages for detecting weapons in images and videos. It includes practical implementation steps such as annotation formatting, configuration setup, and training with Ultralytics' YOLO framework, making it a comprehensive starting point for security applications and smart surveillance systems.

## Background

As crime rates fluctuate and public safety becomes a growing concern, the demand for innovative solutions to enhance security and ensure peace of mind has never been more critical. This project is designed to learn how to implement an advanced machine learning technique, object detection, and use it to solve real-world problems. By exploring the capabilities of YOLO11 (You Only Look Once), an object detection algorithm known for its exceptional speed and accuracy, we will embark on a journey to develop and deploy a system capable of recognizing weapons in diverse settings, ultimately contributing to safer community environments.

## Outline

- Introduction to Object Detection and YOLO11

    * Overview of object detection and its application
    * Introduction to YOLO11
    * Perform object detection using YOLO11 pre-trained model

- Data Collection and Preparation
    * Introduction to image annotation using Roboflow
    * Collecting and managing datasets for weapon detection
    * Image data preprocessing for object detection

- Training and Evaluating the YOLO11 Model
    * Understanding YOLO11 architectures and weights.
    * Initiating the training process with YOLO11
    * Evaluating model performance and interpreting results.

## Libraries

```markdown
- ultralytics
- PIL
- pandas
- numpy
- opencv-python
```
    
## Setup

* Make an environment with `python==3.12` using the following command 

``` bash
conda create -n my_env python==3.12
```

* Activate the environment

``` bash
conda activate my_env
``` 

* Install the project dependencies using the following command 

```bash
pip install -r requirements.txt
```

## Demo

https://github.com/user-attachments/assets/0a5baed6-bbc1-473f-ad50-50ff331d7261