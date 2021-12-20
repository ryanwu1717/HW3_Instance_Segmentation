# HW3_Instance_Segmentation

code for  Instance Segmentation Challenge. <br>

download the pretrained weight [here](https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5)

download the last weight [here](https://drive.google.com/file/d/1GIxYkBt7bXU22Rc6IoRF6_0PHRd4GRBL/view?usp=sharing)

## Hardware
● Windows 10 <br>
● Intel(R) CORE i7 7th Gen @ 4.00GHz <br>
● NVIDIA GeForce GTX 1050 Ti <br>

## Introduction and details
There is the outlines in this compitions <br>
1. [Installation](#Installation) <br>
2. [Architecture](#Architecture)<br>
3. [Implement](#Implement) <br>
4. [Testing](#Testing) <br>
5. [Results](#Results)<br>
6. [Reference](#Reference)<br>

## Installation
Using Anaconda and pytorch to implement this method.

    conda create -n maskrcnn python=3.6
    git clone https://github.com/matterport/Mask_RCNN.git

## Architecture
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/architecture1.png) <br> 
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/architecture2.png) <br> 

## Implement
The code is programing on 

    Ubuntu 20.04
    python 3.6
    Nvidia GeForce 1050Ti 
    Tensorflow  1.131.
    keras v2.1.6
    
Train the model 
`python3 samples/coco/coco.py train --dataset=/path/to/coco/ --model=coco`

## Testing
`python3 samples/coco/coco.py evaluate --dataset=/path/to/coco/ --model=last`

## Results
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/1.png) <br> 
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/2.png) <br> 
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/3.png) <br> 
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/4.png) <br> 
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/5.png) <br> 
![image](https://github.com/ryanwu1717/HW3_Instance_Segmentation/blob/main/result/6.png) <br> 

## Reference
#### Detectron2 (https://github.com/matterport/Mask_RCNN)


 
