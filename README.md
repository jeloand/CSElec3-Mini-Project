<h1 align="center">Mini Project: Face Mask Detection</h1>

<div align="center">
  <h4>Face Mask Detection using OpenCV, Keras, TensorFlow, and MobileNet</h4>
</div>

## :file_folder: Folder Structure
    .
    ├── dataset       
    │   ├── with_mask         
    │   ├── without_mask         
    ├── face_detector                    
    │   ├── deploy.prototxt
    │   ├── res10_300x300_ssd_iter_140000.caffemodel
    ├── detect_mask_video.py                    
    ├── mask_detector.model                    
    ├── requirements.txt                    
    ├── train_mask_detector.py                    
    └── README.md
## :key: Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/jeloand/CSElec3-Mini-Project/blob/main/requirements.txt)

## 🚀&nbsp; Installation

1. Download the zip file or clone the repository.
```
$ git clone https://github.com/jeloand/CSElec3-Mini-Project.git
```
2. After obtaining a copy, go to the respective directory and run the following command in your Terminal to install the libraries required.
```
$ pip3 install -r requirements.txt
```
## :game_die: Train the model
Run following command to train the model
```
$ python3 detect_mask_video.py 
```
