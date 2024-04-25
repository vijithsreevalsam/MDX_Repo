PDE4434CW - Coursework 2
This repository contains a demonstration related to PDE4434 CW2 -showcasing the 
detection of UNO Cards using computer vision.
Overview This project aims to detect UNO cards from a camera feed or loaded 
images. UNO cards contain 15 types of classes, each with 4 color sets: blue, yellow, 
red, and green.

Workflow Here is the step-by-step workflow for this coursework:


Approach of Card detection:
Creating a dataset of 15 class images, which include: Numbers from 0 to 9 Wild Wild 
Take 2 Wild Take 4 Skip Reverse Two approaches are followed: OpenCV template 
matching method and Machine Learning approach. Both approaches have their 
advantages and disadvantages. OpenCV's built-in algorithms use feature matching 
through template matching libraries, requiring limited data. However, the resulting 
model may have limitations under different lighting conditions. The Machine 
Learning approach employs CNN (Convolutional Neural Network), which is more 
robust but requires a large amount of data for training, which may be challenging 
with limited PC resources.

Color Detection:
Color detection is handled by OpenCV's HSV (Hue, Saturation, Value) algorithm. Hue 
represents the color, saturation indicates the greenness in the image, and value 
represents the brightness of each pixel. This method provides better performance in 
color detection compared to the RGB format.







Execution Instructions:

Launch CW2_UNO card detection.ipynb to run the card detection program.
Launch SaveImagefromwebCam.ipynb to capture dataset from the camera.
Run Model training in UNO_Card_CNN_CW.ipynb.

Limitations:
The behaviour of card detection may be affected by lighting conditions and 
background.







Submitted by:
Vijith viswan
M00986814
