
# Sign Language Detection 

## Project Overview
This project aims to develop a real-time sign language detection system using computer vision techniques. The system is capable of capturing hand gestures via a webcam, preprocessing the images, and classifying the hand signs into predefined categories. The model used for classification is built using Teachable Machine by Google, ensuring a robust and accurate recognition of sign language gestures.



## Screenshots

![App Screenshot](https://github.com/sharathkumar1996/HandSignRecognition/blob/main/i1.png)


## Project Aproach

Data Collection

The data collection phase involves capturing images of hand signs using a webcam. The data_collection.py script is used for this purpose. Here's a brief overview of the process:

Setup: The script initializes a webcam feed and sets up the HandDetector from the cvzone library.

Image Capture: The script captures images of hand signs in real-time. It detects hands using the HandDetector and crops the hand region from the frame.

Image Preprocessing: The cropped hand images are resized and centered on a white background to standardize the input size.

Saving Images: Preprocessed images are saved to a specified folder upon pressing the 's' key.
## Requirements

OpenCV

MediaPipe

Pillow

NumPy

Pandas

Seaborn

Scikit-learn

Matplotlib

Tensorflow
## Installation

1. Clone Repository
git clone https://github.com/sharathkumar1996/HandSignRecognition.md

2. Install Dependencies
pip install -r requirements.txt

3. Run Data Collection
python data_collection.py

4. Run Test file
python test.py
```
    