On the folder output_images, i have included the results and example images from each stage of the project code.
The pipeline is: 
	Features extraction (HOG, hist, spatial)> Training of the classifier> Sliding Window> Windows Search and Prediction> Heat> Thresholding> Labeling> Final Output - Vehicle Detection
The structure of the folder is as follows:
output_images:
	|
	|_ Final_output> Contains the final output images from the pipeline
	|
	|_ Searching_windows_output> Contains the output images from the windows search and prediction step
	|
	|_ Sliding_window> An image used as an example to visualize the sliding window output
	|
	|_ HOG_features_extraction> An image showing the HOG features extraction output
	|
	|_ heatmap> An image showing the output from the heatmap
			note: an interesting observation is that the output images before and after thresholding the heatmap are quite similar on the image I chose to use as an example