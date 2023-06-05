# 
# [Real Time Object Detection](ObjectDetectionUsingYOLOv3andOpenCV)
<br>
<p align="center">
	<img src="res\yolo.png" width="200px" hight="200px">
</p>

<br>
This project implements an image and video object detection classifier using pretrained yolov3 models. 
The yolov3 models are taken from the official yolov3 paper which was released in 2018. The yolov3 implementation is from [darkne](https://github.com/pjreddie/darknet). Also, this project implements an option to perform classification real-time using the webcam.

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
git clone https://github.com/mucahitbektas/RealTimeObjectDetection.git
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

[<img src="res\yolo.jpg">](https://youtu.be/R9NNlvLbGTc)
<p align="center"><small> Click on the image to play the video on YouTube( https://youtu.be/R9NNlvLbGTc ) </small></p>

# References

1) [YOLO: Real-Time Object Detection Official Website](https://pjreddie.com/darknet/yolo//)

<br>

# Contact with me:
<p align="center">
<a href="mailto:m.bektastr@gmail.com">
<img src="https://img.shields.io/badge/-m.bektastr%40gmail.com-7B83EB?&style=for-the-badge&logo=Microsoft-outlook&logoColor=white" ></a>  
<a href="https://www.linkedin.com/in/mucahitbektas/"><img src="https://img.shields.io/badge/mucahitbektas-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" ></a>  
<a  href="https://www.instagram.com/mucahitbektas_/"> <img src="https://img.shields.io/badge/@mucahitbektas__-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>
 <a  href="https://www.mucahitbektas.com/"><img src="https://img.shields.io/badge/mucahitbektas.com-000000?style=for-the-badge&logo=About.me&logoColor=white"></a>
 </p>
