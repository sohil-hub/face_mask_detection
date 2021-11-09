# face_mask_detection

Deep learning based project to detect the face mask.

## Table of Contents

* [About Project](#about-the-project)
* [Screenshots](#screenshots)
* [Contents of Repo](#contents-of-repo)
* [Installation](#installation)
* [Technologies](#technologies)

## About The Project
This is a Computer Vision based project to detect the face mask on the face. For detecting the face I have used a pretrained facenet model.
For detecting the mask we used CNN using tensorflow.


## Screenshots

## Content of Repo

* **train_mask_detector.py:** Contains the code I used for Building, training and evaluating the tensorflow model for detecting a mask.
* **detect_mask_video.py:** Contains the code of using the webcam, showing the prediction, etc.
* **mask_detector_5.model:** Tensorflow model for detecting a mask.
* **face_detector:** Weights of a pretrained model which detects faces from an image.
* **requirements.txt** Contains the necessary packages for runnig the scripts.

## Installation
* Fork the repository using `git clone https://github.com/sohil-hub/face_mask_detection.git`
* Install the packages using `pip install -r requirements.txt `
* Change the path of line 77-78 in detect_mask_video.py according to your machine.
* run `python detect_mask_video.py` to run the script.

