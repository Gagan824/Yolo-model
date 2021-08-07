# Yolo-model

## YOLOV5s Model
- YOLOv5 is a recent release of the YOLO family of models. YOLO was initially introduced as the first object detection model that combined bounding box prediction and object classification into a single end to end differentiable network. It was written and is maintained in a framework called Darknet. YOLOv5 is the first of the YOLO models to be written in the PyTorch framework and it is much more lightweight and easy to use. That said, YOLOv5 did not make major architectural changes to the network in YOLOv4 and does not outperform YOLOv4 on a common benchmark, the COCO dataset.
- YOLOv5 versions:
https://github.com/ultralytics/yolov5/releases/download/v1.0/model_comparison.png
## Steps :
- git clone https://github.com/ultralytics/yolov5
- cd yolov5
- pip install -r requirements.txt
- then run the file

### You can check the output videos : outpy1_lGGXQzao_AfwP.avi , outpy_ObM23lMC_xgis.avi.

#### Here I have used the pretrained model to detect objects in the video. And here I have manually founded the bounding box details (x,y coordinates, label names etc) after feeding every frame to the yolo model. check YOLOV5.ipynb file.
