# Lane detection using OpenCV

Python implementation of lane detection using image processing algorithms in OpenCV.

## Dataset

This project demonstrates lane detection using a single image from a road dataset. The lanes are marked by a solid white line (on the right) and alternating short line segments with dots (on the left).

![Test_image](https://user-images.githubusercontent.com/87779103/137095226-2112825e-02d0-49c3-b0c6-7f39d3f86bcc.jpg)


## Image processing pipeline

1. Loading of test image
2. Detect edges (Gray scaling, Gaussian smoothing, Canny edge detection)
3. Define region of interest
4. Apply Hough transforms

