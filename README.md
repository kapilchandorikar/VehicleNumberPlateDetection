# VehicleNumberPlateDetection

Identify the license plate in the image and do an OCR to extract the characters from the detected license plate.

Framework used:   
* Darknet written in C and CUDA
* YOLO v3

### Dataset
The json dataset has been processed:   
* The image file are downloaded from the links provided
* The bounding box coordinates are converted in the format required by YOLO
* All the images and annotation data files are stored in the images directory in this GitHub repository.

### Model Customization
The modified configuration files for implementing number plate detection in YOLO are stored in the custom_yolo_files directory and the Google Drive folder.    

The model for number_plate detection has been trained and the model weights are saved on the Google Drive as they exceed the size limit allowed by GitHub.   

Google Drive Folder containing the model weights for number plate detection YOLOv3 model:   
https://drive.google.com/open?id=12QSC615CM-0Van9cP7S32gcBtYhnbyUE
