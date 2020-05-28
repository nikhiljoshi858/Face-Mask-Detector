# Face-Mask-Detector
This project is a face mask detector which detects if a person is wearing a face mask or not. It can used on images and web cam feeds. It is built using Tensorflow

<h3>Usage:</h3>

<h4>detect_mask_image.py file</h4>
This file is used to run the model on images.
<h5>Syntax: python detect_mask_image.py --image path/to/the/image</h5>

<h4>detect_video_image.py file</h4>
This file is used to run the model on videos i.e. web cam feeds .
<h5>Syntax: python detect_video_image.py</h5>

<h4>plot.png file</h4>
This file contains the plot of accuracy and loss vs no. of epochs generated using matplotlib library of Python.

<h4>train_mask_detector file</h4>
This is a Python script used to train the model. You can tweak with the parameters and hyper parameters if you want and look out for the results.

<h4>mask_detector file</h4>
This is the trained model saved from the previous file.

<h4>Dataset folder</h4>
This folder contains the images used as the dataset for training. It contains 2 classes of images: with mask and without mask.

<h4>Examples folder</h4>
This folder contains some test images you can try your model on.

<h4>Face_detector folder</h4>
It contains the pre trained model for face detection and the prototxt file.

<h3>Results:</h3>
Some results can be found in the results folder in the repository.
