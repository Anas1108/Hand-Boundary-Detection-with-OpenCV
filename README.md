# Hand Boundary Detection with OpenCV

## Introduction
This repository contains a script that utilizes OpenCV to find the boundary of a hand in an image and display it on the original image.

## Requirements
- Python 3.x
- OpenCV
- Numpy

## Usage
The script can be run from the command line with the following command:
- python hand_boundary_detection.py --input <path_to_image>


## Methodology
The following steps are taken in the script to find the hand boundary:
1. Read the input image using OpenCV
2. Convert the image to grayscale for easier processing
3. Apply Gaussian blur to reduce noise in the image
4. Use Canny edge detection to find edges in the image
5. Find contours in the image using the edges found in step 4
6. Select the contour with the largest area, which is assumed to be the hand
7. Draw the boundary of the hand on the original image
8. Display the image with the hand boundary drawn

## Conclusion
The script successfully finds the boundary of a hand in an image and displays it on the original image. The methodology used in the script can be modified for other object boundary detection tasks.
