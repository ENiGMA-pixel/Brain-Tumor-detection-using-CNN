Brain-Tumor-Detector:

Building a detection model using a convolutional neural network in Tensorflow & Keras.Used a brain MRI images data founded on Kaggle.

About the data:

The dataset contains 2 folders: yes and no which contains 253 Brain MRI Images. The folder yes contains 155 Brain MRI Images that are 
tumorous and the folder no contains 98 Brain MRI Images that are non-tumorous.

Data Preprocessing:

For every image, the following preprocessing steps were applied:

		1.Crop the part of the image that contains only the brain (which is the most important part of the image).
		2.Resize the image to have a shape of (240, 240, 3)=(image_width, image_height, number of channels): because images in the dataset come
		  in different sizes. So, all images should have the same shape to feed it as an input to the neural network.
		
Data Split:

The data was split in the following way:

	-70% of the data for training.
	-30% of the data for testing.
