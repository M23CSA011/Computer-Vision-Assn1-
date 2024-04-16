# Harris Corner Detection and Stereo Reconstruction

## Harris Corner Detection

### Implementation
To implement the Harris Corner detection technique, the following steps will be followed:
1. Implement the algorithm from scratch without using any in-built functions.
2. Adjust parameters such as the window size and threshold value to optimize corner detection performance.
3. Modularize the code to take images from a folder as input.
4. Compare the performance of the implemented algorithm with corner detection libraries from OpenCV.

### Code
The code for Harris Corner detection and comparison with OpenCV library will be provided separately.

## Stereo Reconstruction

### Approach
Consider two stereo images I1 (“bikeL.png”) and I2 (“bikeR.png”) of a static scene captured from a stereo camera with the given intrinsic matrices of both the cameras in the file (“bike.txt”). The stereo 3D reconstruction algorithm will be implemented to find the:
- Disparity map
- Depth map (depth map at each pixel)
- 3D point cloud representation of the underlying scene.

### Implementation
The stereo reconstruction algorithm will be implemented using the intrinsic matrices and stereo images provided.

## Epipolar Geometry

### Given Images
Consider two images I1 (“000000.png”) and I2 (“000023.png”) of a static scene captured from a single camera with the given Fundamental matrix F (“FM.txt”).

### Steps
1. Write code to find the epipolar lines and draw them on both images.
2. Consider uniformly spaced 10 pixels on the epipolar line in the first image and find the corresponding pixels on the second epipolar line.
3. Similarly, consider uniformly spaced 10 pixels on the epipolar line in the second image and find the corresponding pixels on the first epipolar line. Search only on the epipolar lines.

### Implementation
The code to find and draw epipolar lines, and to find corresponding pixels on epipolar lines will be provided.

## Image Source
All the required images and files are present in the following location:
[Image and Data Repository](https://drive.google.com/drive/folders/1la4hwF_n4g7T25d2gyCF1ob3HJOir3Th?usp=sharing)
