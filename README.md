

##Advanced Lane Finding Project##
	In this project, your goal is to write a software pipeline to identify the lane boundaries in a video.  

** the package needed
os
cv2
glob
pickle
random
numpy
PIL
matplotlib
moviepy.editor
Ipython.display

The goals / steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, edge detection based on Sobel(to catch x,y,mag features), to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Using statistical histogram and sliding window to detect lane pixels and fit it by quadratic polynomial to find the lane boundary.
* according to the quadratic polynomials of left and right lands, determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

