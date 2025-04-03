# 🎯 Weapon Detection with YOLOv8 🛡️

Empowering intelligent object detection for enhanced security and analysis.

![image](https://github.com/user-attachments/assets/c0ea93ac-1653-4aeb-8d73-1c7bef392da8)


## 🚀 Project Overview

This project leverages the cutting-edge YOLOv8 object detection model to accurately identify and localize various weapons within images and GIF sequences. By training on a custom dataset tailored for weapon recognition, we achieve robust detection capabilities, crucial for applications ranging from security surveillance to content analysis.

## 🛠️ Key Functionalities

* **Custom Dataset Handling:** Streamlined data preparation using `data.yaml` to define dataset paths and class labels.
* **Efficient YOLOv8 Training:** Optimized model training with `ultralytics` for rapid and accurate learning.
* **Real-time Inference:** Swift weapon detection on images and GIFs with clear visualization of bounding boxes and class labels.
* **Visual Output:** Clear and concise display of detection results using `result.show()`.

## ⚙️ Workflow

1.  **Dataset Configuration:**
    * Creation of `data.yaml` to specify training, validation paths, and class details.
2.  **Model Training:**
    * Installation of `ultralytics` for YOLOv8 integration.
    * Execution of `yolo` command to train the YOLOv8s model with defined parameters.
3.  **Inference and Visualization:**
    * Loading the trained model from `/kaggle/working/runs/detect/train/weights/best.pt`.
    * Iterating through test images and GIFs for detection.
    * Displaying results with bounding boxes and class labels.

## 📊 Results

The YOLOv8 model demonstrates high accuracy in detecting weapons, providing:

* Precise bounding box localization.
* Accurate class labeling.
* Effective visualization of detection results.

## 💻 Tech Stack

* **Python:** Core programming language.
* **PyTorch:** Deep learning framework.
* **Ultralytics (YOLOv8):** State-of-the-art object detection.
* **PIL (Python Imaging Library):** Image processing.

## 📁 Project Structure
