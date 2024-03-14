
# Cartoonification with OpenCV and Python

This repository provides Python code to apply a cartoon effect to images using OpenCV and Python. The code includes functions for reading image files, edge detection, color quantization using k-means clustering, and applying the cartoon effect.

## Overview

Cartoonification is a process of transforming images into cartoon-like representations. The code in this repository offers a simple implementation of cartoonification using the following steps:

1. **Read Image**: Load an image file from disk and convert it to RGB format.
2. **Edge Detection**: Detect edges in the image using adaptive thresholding.
3. **Color Quantization**: Simplify the colors in the image using k-means clustering.
4. **Combine Edges and Colors**: Combine the edge mask and quantized colors to create a cartoon-like effect.
