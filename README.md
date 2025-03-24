# License Plate Recognition (LPR) Project

This project focuses on detecting and recognizing vehicle license plates from images. It involves two distinct tasks:

1. **License Plate Detection**: Identifying and locating the license plates in the given images.
2. **License Plate Character Recognition**: Deciphering the alphanumeric characters inscribed on the detected license plates.

## Dataset Overview

The dataset consists of two main sets for training and testing the model:

### 1. **Training Set 1 (Detection)**:
   - **Size**: 900 images
   - **Description**: Each image contains a single car with its license plate. The annotations provide the coordinates of a bounding box (ymin, xmin, ymax, xmax) that encapsulates the license plate.
   
### 2. **Training Set 2 (Character Recognition)**:
   - **Size**: 900 images
   - **Description**: This set contains images of license plates only. The annotations contain the alphanumeric text present on each license plate.

### 3. **Test Set**:
   - **Size**: 201 images
   - **Description**: The test set is similar to the first training set, containing images with vehicles and their license plates. The task is twofold: detect the license plates and recognize the characters on them.

## Project Workflow

### Step 1: License Plate Detection
   - **Goal**: Detect and locate the license plates within vehicle images.
   - **Approach**: Use an object detection model such as YOLO, Faster R-CNN, or SSD to predict bounding boxes around the license plates in the images.

### Step 2: License Plate Character Recognition
   - **Goal**: Recognize the alphanumeric characters on the detected license plates.
   - **Approach**: Use Optical Character Recognition (OCR) techniques like Tesseract, or deep learning models such as Convolutional Neural Networks (CNN) for text recognition.

## Requirements

- Python 3.x
- Libraries:
  - `tensorflow` or `pytorch` for deep learning
  - `opencv-python` for image processing
  - `matplotlib` for visualizing the results
  - `tesseract` (optional) for OCR-based character recognition
  - `numpy` and `pandas` for data manipulation
 
## 🌟 About Me

Hi there! I'm **Vineeth Raja Banala**, a passionate machine learning enthusiast with a Master's in Data Science from Heriot-Watt University. I specialize in developing and deploying machine learning models that turn data into actionable insights. My goal is to bridge the gap between complex data challenges and impactful solutions to drive business growth and innovation.


