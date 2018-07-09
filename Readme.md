Computer vision is a pretty great part in the field of Artificial Intelligence. One of it's subbrach is Object detection. Object detection refers to the capability of computer and sorftware systems to locate objects in an image and identify each object.

Using modern methods like deep learning for object detection is a hard task. I came a cross a prebuild/pretrained object detection by John Olafenwa and his team called ImageAI, a python library that lets programmers and software developers to easily intergrate state-of-the-art computer vision technologies into their existing and new applications, using just few lines of code.

Let's get started;

first, install python on your system.
 https://python.org, prefer python3.

# Install dependecies
---------------------------------
pip install tensorflow
---------------------------------
pip install scipy
---------------------------------
pip install numpy
---------------------------------
pip install opencv-python
---------------------------------
pip  install pillow
---------------------------------
pip install matplotlib
---------------------------------
pip install keras
---------------------------------

# installing ImageAI
pip install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.1/imageai-2.0.1-py3-none-any.whl

file "resnet50_coco_best_v2.0.1.h5" is the  RetinaNet model file that will be used for object detection.
Download it from http://bit.ly/2KZIBUu


Run object_detection1.py and wait the results to print out at the console

You can replace the image Addis_Ababa.jpg with your own image.

ImageAI supports many powerful customization of the object detection process. One is the ability to extract the image of each object detected in the image. By parsing the parameter 'extract_detected_objects = True' into the 'detectObjectsFromImage' fuction, the object ditection class will create a folder for the image objects, extract each image, save each to the new folder created and return an extra array that contains the path to each of the images

You can find all the details and documentation of how to make use of the above features, as well as other computer vision features contained in ImageAI on the official GitHub repository.

https://github.com/OlafenwaMoses/ImageAI
