# Augmented Reality simple shape detector using OpenCV for >= Android 4.0 #

### What is this repository for? ###

* Uses the camera image to recognize triangles, rectangles and circles. It can also be configured to only detect a certain color (red). If a specific shape is detected the information can be shown on top of each shape as a label describing it (multiple shapes at the same time) or as an image respresenting the shape on top of the camera (only one shape is detected). Additionally also a sound depending on the detected shape can be played.
* Version 1.0

### How do I get set up? ###

* IDE: Android Studio (tested with 2.1.2)
* Android SDK
* Dependencies: OpenCV 3.0.0 library (included)
* Images location: res/drawable | Sounds location: res/raw
* Mode (label/image): Flag in MainActivity
* Mode (all colors / red only): Flag in MainActivity
* Make sure the app has the required permission on start, as there is no runtime-check yet! (Camera)

### Who do I talk to? ###
* Repo owner and developer: android@michaeltroger.com

### Credits ###
* The shape detection is based on Nash's shape detection https://github.com/bsdnoobz/opencv-code/blob/master/shape-detect.cpp His version is based on OpenCV 2 for the PC and usable for normal images.
