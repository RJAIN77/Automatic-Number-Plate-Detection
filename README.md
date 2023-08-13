# Automatic-Number-Plate-Detection

DETECT LICENSE PLATES WITH TENSORFLOW, OPENCV AND OCR LIBRARIES 
In the following project, we will recognize License number plates using the Python programming language. We will utilize OpenCV for this project in order to identify the license number plates and the python pytesseract for the characters and digits extraction from the plate. The results have shown that the trained neural network is able to perform with high accuracy of nearly 90-95 percent in recognizing license plates.

First, we have to collect the images. Then we will label those images for the object detection of the Number Plate using the Image Annotation Tool which is open-source software developed in Python GUI and available on GitHub.Then after labeling the image we will work on data preprocessing, and build and train a deep learning object detection model (Inception Resnet V2) in TensorFlow 2. Once we have done with the Object Detection model training process, then using this model we will crop the image which contains the license plate which is also called the region of interest (ROI), and pass the ROI to Optical Character Recognition API Tesseract in Python (PyTesseract). As well extract text from images

