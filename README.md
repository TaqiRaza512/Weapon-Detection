# Weapon Detection using YOLOv8

This project demonstrates the process of weapon detection using the YOLOv8 (You Only Look Once) object detection model. It involves training a YOLOv8 model on a custom dataset consisting of various types of weapons and running inference on test images to detect these weapons in real-time.

![image](https://github.com/user-attachments/assets/c0ea93ac-1653-4aeb-8d73-1c7bef392da8)


The project utilizes the `Ultralytics YOLOv8` package, which simplifies the process of building and deploying object detection models.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Training](#training)
- [Inference](#inference)
- [Results](#results)
- [License](#license)

## Project Overview

The goal of this project is to train a YOLOv8 model for detecting nine types of weapons in images. The weapons included in the dataset are:

- Automatic Rifle
- Bazooka
- Grenade Launcher
- Handgun
- Knife
- Shotgun
- SMG
- Sniper
- Sword

After training the model, the weapon detection model is tested on a set of images and the detected objects are visualized.

## Installation

To get started with the project, first install the required dependencies.

### 1. Install Ultralytics YOLOv8

YOLOv8 is available through the `ultralytics` Python package. To install it, run:

```bash
pip install ultralytics
