# Video Analysis with Tensor Decomposition

This repository contains the code files for the Medium Article Video Analysis 
with Tensor Decomposition in Python.


## Files
### Videos

* commute.MOV: 10s video of cars on the highway, taken during my afternoon commute
* patio.MOV: 10s video of looking around the empty patio of one of my favorite cafes
* parking_lot.MOV: 10s video of a parking lot

### Analysis

* Development Notebook: Jupyter Notebook containing the analysis of the three previous videos

### License
* LICENSE: MIT license for this project

## Installation

To install on a local machine, simply fork this repository and download all the files. 
In order to run the notebook, the following libraries are needed:
* OpenCV (cv2)
* NumPy
* random
* TensorLy

The project was developed with Python3. It will take quite a while to run due to the 
tensor computations involved, so I recommend running it by itself.

## Results

This analysis shows how extracting core tensors using Tucker Decomposition allows making
more robust comparisons of videos and clustering them together. For more details, please see
the Medium article referenced above.

