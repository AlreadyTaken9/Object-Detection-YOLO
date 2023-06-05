# 
# [Real Time Object Detection](ObjectDetectionUsingYOLOv3andOpenCV)
<br>
<p align="center">
	<img src="res\yolo.png" width="200px" hight="200px">
</p>

<br>
This project implements an image and video object detection classifier using pretrained yolov3 models. 
The yolov3 models are taken from the official yolov3 paper which was released in 2018. The yolov3 implementation is from (https://github.com/AlreadyTaken9/Object-Detection-YOLO). Also, this project implements an option to perform classification real-time using the webcam.

With this model, objects given in the labels list can be recognized.

<br>

```
labels = ["person","bicycle","car","motorcycle","airplane","bus","train","truck","boat","trafficlight",
		"firehydrant","stopsign","parkingmeter","bench","bird","cat","dog","horse","sheep","cow",
		"elephant","bear","zebra","giraffe","backpack","umbrella","handbag","tie","suitcase","frisbee",
		"skis","snowboard","sportsball","kite","baseballbat","baseballglove","skateboard","surfboard",
		"tennisracket","bottle","wineglass","cup","fork","knife","spoon","bowl","banana","apple",
		"sandwich","orange","broccoli","carrot","hotdog","pizza","donut","cake","chair","sofa",
		"pottedplant","bed","diningtable","toilet","tvmonitor","laptop","mouse","remote","keyboard",
		"cellphone","microwave","oven","toaster","sink","refrigerator","book","clock","vase",
		"scissors","teddybear","hairdrier","toothbrush"]
```
<br>

# How to use?

1 ) Clone the repository

```
git clone https://github.com/AlreadyTaken9/Object-Detection-YOLO
```

2 ) Move to the directory
```
cd RealTimeObjectDetection
```
3.1 ) To infer real-time on your webcam
```
python3 yolo_objectdetect_fromWebCam.py
```
3.2 ) To infer real-time on IPCam
```
python3 yolo_objectdetect_fromIPCam.py
```


Note: This works considering you have the `weights` and `config` files at the yolov3/model directory.
<br/>

If the files are located somewhere else then mention the path while calling the `yolo_objectdetect_fromXXXCam.py`. For more details
```
yolo.py --help
```

<br>

> NOTE: If you want to take images over the IP camera, you can use the applications that you can search for 'IP Webcam' on Android or IOS market platforms.

<br>

# Inference in Real-time

[<img src="res\yolo.jpg">](https://youtu.be/8_ayzLbepI4)
<p align="center"><small> Click on the image to play the video on YouTube( https://youtu.be/8_ayzLbepI4 ) </small></p>

# References

1) [YOLO: Real-Time Object Detection Official Website](https://github.com/AlreadyTaken9/Object-Detection-YOLO)

<br>
