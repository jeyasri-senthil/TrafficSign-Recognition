### ***ROAD SIGN DETECTION USING YOLOv5***

*This repository contains the code for detecting road signs using the YOLOv5 object detection framework. The YOLO algorithm is known for its real-time object detection capabilities, and YOLOv5 is an optimized and efficient version of the original YOLO.*

![detections](https://github.com/jeyasri-senthil/RoadSign-Detection/assets/108861190/e337c71d-78e1-4fcb-bb9e-467832720868)

### ***Dataset***

*The dataset used for this project is sourced from Kaggle, specifically the "Road Sign Detection" dataset by Andrewmvd. It contains annotated road sign images for training and evaluation.*

### ***Convert PASCAL VOC to YOLO Format***

*Before training the YOLOv5 model, we need to convert the annotations from the PASCAL VOC format to the YOLO format. To do this, run the `convert_voc_to_yolo()` function from the `preprocessing` module.*

### ***Setting up YOLOv5***

*Clone the YOLOv5 repository and install the required dependencies to get started with training and detection.*

### ***Training the Model***

*Training the Model*

*python train.py --img 320 --batch 16 --epochs 50 --data VOC.yaml --weights yolov5s.pt --workers 2*

*Feel free to adjust the training parameters as per your hardware and requirements.*

### ***Making Detections***

*After training the model, and then you can make detections on new images using the trained weights.*

### ***Acknowledgments***

*Special thanks to the authors of the YOLOv5 repository and Andrewmvd for providing the "Road Sign Detection" dataset. Your contributions have made this project possible.*

### ***HAPPY LEARNING!***

