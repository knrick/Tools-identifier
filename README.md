# Tools-identifier

## This classifier is based on this repo:
https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10

## Guide on using the finished model
### Requirements
Anaconda with Python 3.6

### Setup
conda create -n tensorflow1 pip python=3.5

activate tensorflow1

(tensorflow1)  pip install opencv

(tensorflow1)  pip install numpy

(tensorflow1)  pip install tensorflow

(tensorflow1)  pip install jupyter

(tensorflow1)  pip install matplotlib

I might missed some packages however it won't be hard to identify and install them.

### Use
To test your object detector, move a picture of the object or objects into the \object_detection folder, and change the IMAGE_NAME variable in the Object_detection_image.py to match the file name of the picture. Alternatively, you can use a video of the objects (using Object_detection_video.py), or just plug in a USB webcam and point it at the objects (using Object_detection_webcam.py).

To run any of the scripts, type “idle” in the Anaconda Command Prompt (with the “tensorflow1” virtual environment activated) and press ENTER. This will open IDLE, and from there, you can open any of the scripts and run them.

If everything is working properly, the object detector will initialize for about 10 seconds and then display a window showing any objects it’s detected in the image.
