Description
===========
Detects epidermal abnormalities from a picture
Classifies to identify skin disease
Uses opencv to segment and isolate objects from an image

Progress
========
Created segmentation scripts
Created simple neural network

Next Step
=========
Mine data to make training set


Current issues:
==============
Sometimes contours are formed around blank space, and a blank object is cropped out

Sometimes multiple objects are clustered together as one object
Implement a fix with watershed: https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_watershed/py_watershed.html