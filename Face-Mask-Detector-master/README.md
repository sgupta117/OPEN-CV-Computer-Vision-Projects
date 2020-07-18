# Face detection with OpenCV and deep learning

When using OpenCV’s deep neural network module with Caffe models, you’ll need two sets of files:

1) The .prototxt file(s) which define the model architecture (i.e., the layers themselves)
2) The .caffemodel file which contains the weights for the actual layers

Both files are required when using models trained using Caffe for deep learning.

 1) DataSets contains both masks and Non masks faces to train our Neural Network
 2) To train the model just run file : train_mask_detector.py
 3) To run the live video streaming mask detection just run : detect_mask_video.py file.
 

* Glimpse of the web app:
![GIF](readme_resources/mask_detector1.gif)
