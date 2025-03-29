# Image-Recognition
Image Recognition in Python using OpenCV. 
Face Detection is done using Haar Cascade, and Recognition is done using the Linear Binary Pattern Histogram Algorithm.
For more details, refer [this](http://docs.opencv.org/trunk/d7/d8b/tutorial_py_face_detection.html) and [this](http://docs.opencv.org/2.4/modules/contrib/doc/facerec/facerec_tutorial.html)

####How to Use

     git clone https://github.com/sarthakagarwal18/Image-Recognition.git
     python Face_Recog.py test.jpg

![](/screenshot.png?raw=true)

*Note*: The Recognition is done through numerical labels. For example: 2 corresponds to Leonardo DiCaprio. 
Also, since the training dataset considered here is very small, the recognition can be inaccurate. Adding more training images will increase the accuracy.

Inspired from [this](https://github.com/JeeveshN/Face-Recog-Tool) repository.
