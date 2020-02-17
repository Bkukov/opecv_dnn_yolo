# Yolov3 with cv2 DNN Module

I've implemented people tracker using the opencv dnn module to run a yolov3 model trained on the coco set. 

Currently I'm ignoring detections that aren't people but that could be easily removed. My implementation combines the centroid
tracker algorithm from pyimagesearch along with the opencv-dnn module guide. I'm looking to further this project by combining
my detections with a deepSORT algorithm for tracking sine this current algorithm struggles with faster objects, occlusion and 
similar objects. 

This project requires that you setup tensorflow and the opencv dnn module for which there are many guides online. It will not
work out of the box unless you first set up tensorflow,cuda, and opencv-contrib/dnn. 

This repo also doesn't hold the yolov3.weights file but that could be obtaned online.

Adding the following links for credit/resources for setting up your own environment.

https://www.pyimagesearch.com/2019/12/09/how-to-install-tensorflow-2-0-on-ubuntu/
https://www.pyimagesearch.com/2020/02/03/how-to-use-opencvs-dnn-module-with-nvidia-gpus-cuda-and-cudnn/
https://www.pyimagesearch.com/2020/02/10/opencv-dnn-with-nvidia-gpus-1549-faster-yolo-ssd-and-mask-r-cnn/
