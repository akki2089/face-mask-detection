<h1 align="center">Face Mask Detection</h1>

<h4>Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.</h4>

![video](https://user-images.githubusercontent.com/43907561/177964905-4a449c5c-ba49-4717-85cd-201cee28f5b9.gif)

# Framework/Libraries Used
OpenCV
Keras
TensorFlow
Scipy


## :file_folder: Dataset
The dataset used can be downloaded here - [Click to Download](https://drive.google.com/drive/folders/108KDCyi_J2oO4lqTFe2u_uwymeKiUW-Z?usp=sharing)

This dataset consists of __3833 images__ belonging to two classes:
*	__with_mask: 1915 images__
*	__without_mask: 1918 images__

The images used was real images of faces wearing masks. The images was collected from the __Kaggle datasets__

## :key: Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here](https://github.com/akki2089/face-mask-detection/blob/master/requirements.txt)

## :key: Results

#### Our model gave 98% accuracy for Face Mask Detection after training via <code>tensorflow-gpu==2.5.0</code>

<a href="https://colab.research.google.com/drive/1anYeUekLC7aQjmVms3vJ1GwI1NwNsNZa"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

#### We got the following accuracy/loss training curve plot
![](https://github.com/akki2089/face-mask-detection/blob/master/plot.JPG)

