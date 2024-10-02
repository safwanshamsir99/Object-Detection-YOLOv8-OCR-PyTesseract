# Object-Detection-YOLOv8-and-OCR-PyTesseract
Training materials to perform computer vision object detection using YOLOv8 and optical character recognition (OCR) using PyTesseract.

## Getting Started

1. YOLOv8 is on of the latest version of the YOLO (You Only Look Once) object detection model developed by Ultralytics. It’s super fast and accurate, making it great for real-time applications. You can refer the YOLOv8 documentation here: https://docs.ultralytics.com/

2. PyTesseract is a Python wrapper for Google’s Tesseract-OCR Engine. It allows you to easily extract text from images using OCR (Optical Character Recognition). You can read more here: https://github.com/h/pytesseract and download the software here: https://github.com/UB-Mannheim/tesseract/wiki

### File Descriptions

1. **images/** <br />
   Contains 100 frames of `mycarplate.mp4` video
2. **README.md** <br />
   Repositories documentation
3. **best.pt** <br />
   Best YOLOv8 model when trained on the car plate images, annotated using Roboflow.
4. **Car plate.v1i.yolov8.zip** <br />
   Annotated car plate images, downloaded from Roboflow. 
5. **car_plate_data.txt** <br />
   List of the detected car plate, result by perform OCR using PyTesseract
6. **coco1.txt** <br />
    Contains label name used when annotate the car plate on Roboflow.
7. **img.py** <br />
    Contains Python scripts to divided the `mycarplate.mp4` video into frames defines by the script user using OpenCV library.  
8. **imgdeletetyolo.py** <br />
    Contains Python scripts to delete unannotated images (if the car plate images are annotated using other tools than Roboflow such as labelme)
9. **mycarplate.mp4** <br />
    Video of driving cars on a road used to train the YOLOv8
10. **stdr.py** <br />
    Video of driving cars on a road used to train the YOLOv8
11. **Object_Detection__YOLOv8_OCR_PyTesseract.ipynb** <br />
    Contains step-by-step instruction on how to perform object detection & OCR and code to train the YOLOv8 model on annotated car plate dataset using Command-Line-Interface (CLI)


### Folder Structure

```
.
├── README.md
├── images/
├── best.pt
├── Car plate.v1i.yolov8.zip
├── car_plate_data.txt
├── coco1.txt
├── img.py
├── imgdeletetyolo.py
├── mycarplate.mp4
├── stdr.py
└── Object_Detection__YOLOv8_OCR_PyTesseract.ipynb
```

## Learning resources

* Roboflow: https://roboflow.com/
* Ultralytics documentation: https://docs.ultralytics.com/
* Ultralytics CLI: https://docs.ultralytics.com/usage/cli/
* Download PyTesseract: https://github.com/UB-Mannheim/tesseract/wiki

