# Real-Time-Object-Detection-Using-Pretrained-YOLO
Object detection using YOLO object detector

### Detect objects in real time using Deep Learning, OpenCV, and Python.

Using YOLOv3 in this project, in particular, YOLO trained on the COCO dataset.

The COCO dataset consists of 80 labels, including, but not limited to:

- People
- Bicycles
- Cars and trucks
- Airplanes
- Stop signs and fire hydrants
- Animals, including cats, dogs, birds, horses, cows, and sheep, to name a few
- Kitchen and dining objects, such as wine glasses, cups, forks, knives, spoons, etc.
…and much more!

You can find a full list of what YOLO trained on the COCO dataset can detect <a href="https://github.com/sejalsahu01/Real-Time-Object-Detection-Using-Pretrained-YOLO/blob/main/coco.names" target="_blank"><b>using this link.</b></a>

- yolo-coco : The YOLOv3 object detector pre-trained (on the COCO dataset) model files. These were trained by the <a href="https://pjreddie.com/darknet/yolo/" target="_blank"> <b>Darknet team.</b> </a>

---
## Installation

- `pip install numpy`
- `pip install opencv-python`
- `pip install imutils`

## To Run the project
1. Clone this repository:
```bash
git clone https://github.com/sejalsahu01/Real-Time-Object-Detection-Using-Pretrained-YOLO.git
```

2. Navigate to the project directory:
```bash
cd Real-Time-Object-Detection-Using-Pretrained-YOLO
```

3. Execute the script:
```bash
python real_time_object_detection.py
```
---
## Screenshot
<img src="https://github.com/yash42828/YOLO-object-detection-with-OpenCV/blob/master/real-time-object-detection/real_time.gif">
Notice how our deep learning object detector can detect not only a person, but also the sofa and the chair next to person — all in real-time!

