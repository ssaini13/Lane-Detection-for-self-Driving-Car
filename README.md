# Lane detection using OpenCV

Python implementation of lane detection using image processing algorithms in OpenCV.

## Dataset

This project demonstrates lane detection using a single image from a road dataset. The lanes are marked by a solid white line (on the right) and alternating short line segments with dots (on the left).

![image](https://user-images.githubusercontent.com/87779103/137097383-2992fcc2-ff97-46d8-baea-36880c676570.png)


## Image processing pipeline

1. Loading of test image
2. Detect edges (Gray scaling, Gaussian smoothing, Canny edge detection)
3. Define region of interest
4. Apply Hough transforms

