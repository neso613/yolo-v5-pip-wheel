# yolo-v5-pip-wheel
YOLOv5 model in TensorFlow Lite (TFLite) for Object Detection over 1000 classes(coco dataset).\
Note: Images as input are only supported now. 

#### Note: This wheel works on image data only, adding video stream as input is the future work.

## Installation
- pip3 install yolo-v5-tflite [link](https://pypi.org/project/yolo-v5-tflite/1.0/)

## How To Run
```
from yolo_v5_tflite.yolo_v5 import detect
detect('zidane.jpg')
```
