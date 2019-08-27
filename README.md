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

### Number Plate Detection Notebooks
[01 Environment Set-up](https://github.com/kapilchandorikar/VehicleNumberPlateDetection/blob/master/01%20Environment%20Set-up.ipynb) - Setting up the YOLOv3 model using the Darknet framework   
[02 Data Preparation](https://github.com/kapilchandorikar/VehicleNumberPlateDetection/blob/master/02%20Data%20Preparation.ipynb) - Processing the dataset, converting formats, and splitting into train and test set   
[03 Training the License Plate Detection Model](https://github.com/kapilchandorikar/VehicleNumberPlateDetection/blob/master/03%20Training%20the%20License%20Plate%20Detection%20Model.ipynb) - Modifying the YOLOv3 model to detect number_plate and training on the train set   
[04 Detecting the number plate](https://github.com/kapilchandorikar/VehicleNumberPlateDetection/blob/master/04%20Detecting%20the%20number%20plate.ipynb) - Testing and detecting number plates from test images

Google Drive Folder containing the model weights for number plate detection YOLOv3 model:   
https://drive.google.com/open?id=12QSC615CM-0Van9cP7S32gcBtYhnbyUE
