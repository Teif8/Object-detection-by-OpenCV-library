# Object-detection-by-OpenC
This repository provides code and examples for implementing Object Detection using the OpenCV library in Python. It includes multiple object detection techniques, pre-trained models, and custom scripts to help identify objects in images and video streams.

Features:

	•	Pre-Trained Models: Implement object detection using pre-trained models such as Haar Cascades, HOG + SVM, YOLO, and SSD.
	•	Real-Time Detection: Demonstrates how to use OpenCV with live video streams from webcams or video files.
	•	Custom Object Detection: Allows training of custom object detectors using Haar Cascade classifiers.
	•	Bounding Boxes and Labels: Draws bounding boxes and adds labels around detected objects.

Object Detection Techniques:

	1.	Haar Cascade Classifiers:
	•	Uses pre-trained XML files for face, eye, and body detection.
	•	Example: haarcascade_frontalface_default.xml
	2.	HOG + SVM:
	•	Histogram of Oriented Gradients (HOG) combined with Support Vector Machines (SVM) for detecting objects like pedestrians.
	3.	YOLO (You Only Look Once):
	•	Fast object detection using a pre-trained YOLO model.
	•	Works well for real-time applications.
	4.	SSD (Single Shot Multibox Detector):
	•	Efficient object detection model with pre-trained weights on the COCO dataset.

Structure:

	•	/models: Contains pre-trained model weights and configuration files.
	•	/scripts: Python scripts for running object detection.
	•	/examples: Sample images and video files for testing object detection.
	•	/training: Instructions and code for training custom Haar cascades.

Getting Started:

	1.	Clone the repository.
	2.	Install dependencies: pip install -r requirements.txt.
	3.	Run object detection on images or video using the provided Python scripts.
	•	Example for YOLO:

python yolo_object_detection.py --input input_video.mp4 --output output_video.avi



Requirements:

	•	Python 3.x
	•	OpenCV
	•	Numpy
	•	Pre-trained models (available in /models) 
