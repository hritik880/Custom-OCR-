# Custom-OCR-
Custom Trained Yolo v3 model to find bounding boxes of Labelled Images of Aadhar Card. 
Cropped the identified bounding boxes using OpenCV and extracted text from these images using Tesseract-OCR API.

## Aim of the project
The main aim of this project was to automate the process of Aadhar verification by extracting the text details used for verification purpose from aadhar card mainly the Name, aadar no., Gender, Date of birth,etc.

## What is OCR?
  OCR stands for Object Character Recognition. It is used for reafding the textual data from images. 
  OCR has two major building blocks:
    **Text Detection
    **Text Recognition
    
## 1) Text Detection
   Major Steps Involved were:
   1) Collecting and Labelling the Training Data:
      I collected around 30 Images of different aadahar Card and Labelled them using lablelImg tool.
   2) Training the Data collected for text detection using **YOLOV3** on darknet framework.

## 2) Text Recognition 
   After detecting thre regions where text is present the regions were cropped using **OpenCV** library and then TesseractOCR Library was used to get text into the required format.
   
