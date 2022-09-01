## Ready-to-use Google Colab file: https://colab.research.google.com/drive/1_8Ic31j422YjWGMxzDx0SRIINVQkYad5?usp=sharing
# Yolov7-License-Plate-Recognition-Program
* **License plate part "detect_plate.py"**

https://user-images.githubusercontent.com/77502485/188004361-9a26744d-f553-4336-be2f-947a433ee558.mp4

* **Line crossing cars counter part "detect_cross.py"**

https://user-images.githubusercontent.com/77502485/188002724-7a863ddb-9b28-491e-9af0-32556609bb2f.mp4 



Features
* Count all objetcs by classes and works perfetcly on every image or on a video
* Code can run on Both (CPU & GPU)
* Video/WebCam/External Camera/IP Stream Supported

## It is super easy to run
* **We are going to copy offical yolov7 github page and just add "detect_and_count.py" file. That is all**
* **When you use Google Colab for codes, it will be way easier than working on the local computer**

## Steps to run Code
* clone the repository:
* ```git clone https://github.com/WongKinYiu/yolov7 ```
* ```%cd yolov7```
* install yolov7 model
* ``` !wget "https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt" ```

### Upgrade pip with mentioned command below.
``` pip install --upgrade pip ```

### Install requirements with mentioned command below.
 ``` pip install -r requirements.txt ```

### Using counter
 ``` !python detect_and_count.py --weights /content/yolov7/yolov7.pt --conf 0.1 --source /content/yolov7/inference/images ```
 
