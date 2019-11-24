# sustech-recognition-of-traffic-signs
2019ML-Detection and recognition of traffic signs for self-driving applications


# instruction
## to run this, you should:
### 1. install and learn Tensorflow object detection API.
### 2. install GTSDB and GTSRB dataset.
### 3. copy vrd_evaluation.py to C:\*\models\research\object_detection\utils
### 4. classification:

first,download faster_rcnn_resnet_101 model. then copy it to the sustech-recognition-of-traffic-signs/traffic-sign-detection-master/models(you should new this folder by yourself)
download list: https://drive.google.com/open?id=15OxyPlqyOOlUdsbUmdrexKLpHy1l5tP9

second, run sustech-recognition-of-traffic-signs/traffic-sign-detection-master/Run_models_on_new_images-Copy1.ipynb
(you should edit the path in that file)

### 5. from the step4 we get the output img in sustech-recognition-of-traffic-signs/traffic-sign-detection-master/output.
then run classification.ipynb to get the result.


by Lei
2019.11.24
