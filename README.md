# YOLOER_V2
YOLOER stands for You Only Look Once and Estimate Range while V1 implies the version of object detector (V2 = YOLOv7). The project is about REAL-TIME Object Detection and Distance/Depth Estimation using YOLOv7 object detector. To test the Real-Time functionality immediately, we provide the option of running the model on the webcam. Moreover, the options of testing on recorded videos and images are also provided.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HassanBinHaroon/YOLOER_V2/blob/master/YOLOER_V2.ipynb)

# Demo1 

![](https://github.com/HassanBinHaroon/YOLOER_V2/blob/master/demo/class_and_distance.gif)

# Demo2

![](https://github.com/HassanBinHaroon/YOLOER_V2/blob/master/demo/car.jpg)    

## Table of Contents

 ### 1. Inference on Local Machine Webcam
 ### 2. Inference on Google Colab (quick start)
 ### 3. Training of Object Detector 
 ### 4. Training of Distance Estimator

## Inference on Local Machine Webcam

In order to test any Real-Time system, the most convenient method is to run on the webcam. So, we provide the options of quick inference on a local machine and visualization through the webcam. Some installations are required before running the inference and the following subsection contains the entire method. So follow step by step. 

Moreover, we prefer working in Conda environments and it is recommended to install it first. In case of not have Conda installed, just skip the Conda-specific commands and follow along.  

### Installation Procedure

#### Step 1

     git clone https://github.com/HassanBinHaroon/YOLOER_V2.git

#### Step 2

     cd YOLOER_V2/REAL-TIME_Distance_Estimation_with_YOLOV7
     
#### Step 3     

     pip install -r requirements.txt
     
#### Step 4     

     python detect.py --save-txt --weights yolov7.pt --conf 0.4 --source 0 --model_dist model@1535470106.json --weights_dist model@1535470106.h5 

## Inference on Google Colab (quick start)

Click on the following link.

https://colab.research.google.com/github/HassanBinHaroon/YOLOER_V1/blob/master/YOLOER_V1.ipynb

### Must Do After Clicking

#### >>>>> Change runtime type

![](https://github.com/HassanBinHaroon/YOLOER_V1/blob/master/images/im1.png)

#### >>>>> Select GPU

![](https://github.com/HassanBinHaroon/YOLOER_V1/blob/master/images/im2.png)

#### >>>>> Run All

![](https://github.com/HassanBinHaroon/YOLOER_V1/blob/master/images/im3.png)

### Results Visualization

![](https://github.com/HassanBinHaroon/YOLOER_V1/blob/master/images/results_vis.png)

Note! The project is still in progress.
