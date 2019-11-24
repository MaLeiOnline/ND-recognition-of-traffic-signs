# sustech-recognition-of-traffic-signs
2019ML-Detection and recognition of traffic signs for self-driving applications


# instruction
## to run this, you should:
### 1. install and learn Tensorflow object detection API.
### 2. download GTSDB and GTSRB dataset.
### 3. copy visualization_utils.py to C:\*\models\research\object_detection\utils
### 4. detection:

first,download faster_rcnn_resnet_101 model. then copy it to sustech-recognition-of-traffic-signs/traffic-sign-detection-master/models(you should new this folder by yourself)
, download list: https://drive.google.com/open?id=15OxyPlqyOOlUdsbUmdrexKLpHy1l5tP9

second, run sustech-recognition-of-traffic-signs/traffic-sign-detection-master/Run_models_on_new_images-Copy1.ipynb
(you should edit the path in that file)

### 5. classification:
from the step4 we get the output img in sustech-recognition-of-traffic-signs/traffic-sign-detection-master/output.
then run classification.ipynb to get the result.

## what should do next:
### 1. Find a way to test the model in engineering and evaluate the accuracy.
### 2. Change the model, compare the differences, find the most appropriate one.

## to get other trained models, download in here:
https://github.com/aarcosg/traffic-sign-detection

## you can also learn to train your own models. using this:
https://github.com/MaLeiOnline/train-model-of-object-detection

by Lei, 
2019.11.24
