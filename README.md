# Social-distancing-detection

This project demonstrates a tool that helps customer to monitor social distancing at a work place using tensorflow and OpenCv.

Social distancing is a key step to fight against any pandemic in absence of any pharmaceutical interventions. This will ensure flattern the spread curve and help people work around for basic needs. To maintain social distancing at various workplace/public areas, I have created social distancing detection tool using tensorflow and opencv that detects if people are maintaing safe distance from each other. The analysis is done on real time video stream that consists of three main steps:

1.Detection

2.Calibration

3.Measurement

## Requirement
I have used Macbook Pro for this project.

Open CV: Check out Adrian Rose [link](https://www.pyimagesearch.com/2018/09/19/pip-install-opencv/) for downloading OpenCV.

numpy 1.18.3

imutils 0.5.3
tensorflow 2.1.0

Tensorflow Model:  This project used faster_rcnn_inception_v2_coco model of tensorflow which can be downloaded from the given [link](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md).  Download all the models and unzip them.

Example: tar -xvzf faster_rcnn_inception_v2_coco_2018_01_28.tar.gz

## RUN

Download the source file from the source folder which contains 
1. config_birdeyeview.yml: Configuration file for bird eye view.
2. model_path: directory of the tensorflow model being used in your project. I have used faster_rcnn_inception_v2_coco_2018_01_28.pb
3. Video path: Video used for social distancing detection. You can use any [video](http://www.cvg.reading.ac.uk/PETS2009/a.html) and change under the video_path section.
4. Images used for the static birdview and from the video.
Note: Please verify all these given file path in your code with the saved directory
Run social_distanciation_video_detection.ipynb and it will run detect the social distancing in the given video and save the bird's view. 


## Output
Checkout the videos saved under the video folder.

