"# Image-Video-Analysis" 

The repository has my solution to the following task on Image and Video analysis

1. PrewittEdgeDetector: Prewitt edge detector: gradient filter és nonmaxima-suppression (NMS)
	- Output is two images: 1. gradient magnitute; 2. final result after NMS.

2. OtsuThresholding: Thresholding algorithm by Otsu
	- Output: thresholded image and obtained threshold value.

3. HoughCirlces: Detection of circular object by edge detection and Hough transform for circles
	- Input: 1. image containing circular objects, e.g., cells; 2. range of diameters. 
	- Output: 1. accumulator image; 2. input image with objects detected in given range of diameters.

4. OpticalFlow: Motion tracking of feature points and dense optical flow
	- Input: 1. short video sequence; 2. maximum displacement.
	- Output: 1. points tracked in the video sequence; 2. optical flow of the sequence