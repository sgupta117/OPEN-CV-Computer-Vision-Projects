# Object Detection using Yolo-V3 algorithm

=> You can download the yolo v3 weights from here: https://pjreddie.com/media/files/yolov3.weights

# Dependencies libraries and python packages - How to install:

 => Use file "pytorch_env.yml", it has all the required libraries like Pytorch , numpy and all, Use below commands in anaconda prompt to intall it and create your own virtual envronment.
 
```
conda env create -f pytorch_env.yml 
```

=> If you are getting some errors while installing torch then use below command to install the cpu version of it.
```
conda install pytorch torchvision cpuonly -c pytorch
```

# Test or Run the program:
Run the following command with optional commandline arguments to perform detections on images in 'images' folder. 
By default the 'result' folder will store the output.
```
python detect.py 
```
Run the following command with optional commandline arguments to perform detections on videos
```
python detect_video.py
```

# Some Outputs:
![](https://github.com/sgupta117/Object-Detection-Using-YOLO-3/blob/master/result/det_giraffe.jpg)
![](https://github.com/sgupta117/Object-Detection-Using-YOLO-3/blob/master/result/det_eagle.jpg)
![](https://github.com/sgupta117/Object-Detection-Using-YOLO-3/blob/master/result/det_messi.jpg)
![](https://github.com/sgupta117/Object-Detection-Using-YOLO-3/blob/master/result/det_herd_of_horses.jpg)



Thanks and Happy Coding!!! :)
