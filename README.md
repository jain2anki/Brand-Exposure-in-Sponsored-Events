# Brand-Exposure-in-Sponsored-Events

Real-time logo detection and classification using yolo v3

In this demo, I trained the YOLOv3 algorithm on dataset containing ~500 images of Samsung and Vivo brand logos and their corresponding annotations.
You can see the sample output video [here](https://drive.google.com/open?id=1YOQvpdWiNouumIfovAB4IEB76I7W6v8c)

## Dependencies

Python3, opencv 3, darkflow.

### Getting started

You can download the weights from [here](https://drive.google.com/file/d/1-IPN5lkbeKeFoz4gALIQthWmU5jZzIaO/view?usp=sharing)
detector.py usese the following files :
yolo.names - Names of the brand we are detecting
yolov3_custom.cfg - configuration file for yolo v3 algorithm
yolov3_custom_final.weights - trained weights for detection and localisation (to be downloaded from the given link)

Now, we are ready to run our model. Open the terminal and run the following command

python3 detector.py --image=path_to_image
or
python3 detector.py --video=path_to_video

