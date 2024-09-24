# 🖼️ RealTimeCameraFilters

## General description
This university project implements fundamental image processing camera filters in python. The software can be used as a tool box for testing image filters.
The project contains a graphic user interface to apply filters on a real time camera video flux, allowing to change filters order. Different complexity of filters are implemented.

## Features 

- Simple Filters: Grayscale, Binarization, Histogram Equalization, Negative, Pixelization.
- Edge Detection Filters: Sobel, Laplace, Prewitt
- Morphology: Erosion and Dilation, combinable to achieve closing and opening.
- Real-Time Histogram: Dynamic visualization of the image histogram

## Implementation specification

- Using OpenCL for kernel parallelization.
- SIMD processes with Numpy arrays.

## Install and use !

Prerequisites
To run this project, you must have Python installed on your machine.

**Installing Dependencies**
The required dependencies are listed in requirements.txt. To install them, run:
```
pip install -r requirements.txt
```
**Launching the Project**
To start the image processing interface, run:
```
python src/tifo.py
```
