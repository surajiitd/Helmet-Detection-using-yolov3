# Helmet Detection using YOLOV3
Its a simple YOLO model to detect and count the number of people wearing helmet in a image. this model can be used to detect the intrusion or to find the people ridding bike without helmet.


Getting Started
#### This code is very simple and with the help of little manipulation, you can count the number of detection for a particular detection.
#### or extract the co-ordinates of bounding boxes. download the models, create necessary files and give full path to the models and folder names and run the python script.

#### training:  
  if you want to train your own model, follow the [darknet](https://github.com/AlexeyAB/darknet).
  
Prerequisites  

install python3.  
install pip3.  

Better if you make virtual environment.
##### Make virtual env For Linux : 
```
pip3 install virtualenv
virtualenv helmetenv
source helmetenv/bin/activate
```
install opencv and numpy (requirements.txt files have all dependencies ) :  
```
pip install -r requirements.txt
```
Now Run it:
```
python3 Helmet_detection_YOLOV3.py
```


#### link to model.  
[model](https://drive.google.com/open?id=16yH9M_ovw0cJG4gVKuXTkz_cwYxJtwAk)  

If everything went well. you will get results like this  
![img1](https://github.com/Paatni22/Helmet-Detection-using-yolov3/blob/master/test_out/img3.jpeg)  
![img2](https://github.com/Paatni22/Helmet-Detection-using-yolov3/blob/master/test_out/img4.jpeg)  
![img3](https://github.com/Paatni22/Helmet-Detection-using-yolov3/blob/master/test_out/img.jpeg)  

