## Ready-to-use Google Colab file: https://colab.research.google.com/drive/1_8Ic31j422YjWGMxzDx0SRIINVQkYad5?usp=sharing
# Yolov7-License-Plate-Recognition-Program
* **License plate part "detect_plate.py"**

https://user-images.githubusercontent.com/77502485/188004361-9a26744d-f553-4336-be2f-947a433ee558.mp4

* **Line crossing cars counter part "detect_cross.py"**

https://user-images.githubusercontent.com/77502485/188014954-5e923e3b-c22f-408a-8163-3695cecd0176.mp4


Features
* Count license plates or cars if they cross the line on the screen and take shots of their plates and send them to the database 
* On the database, license plates get applied super-resolution process for better vision
* Code can run on Both (CPU & GPU)

## Steps to run Code
* Download the project files by link: https://drive.google.com/drive/folders/1i2m9rY8wdYdGmz3jo65C1zOcR2O-trln?usp=sharing
* make sure the project files are referenced correctly in colab notebook ( ```%cd /content/drive/MyDrive/yolo_Car/yolov7``` parts): https://colab.research.google.com/drive/1_8Ic31j422YjWGMxzDx0SRIINVQkYad5?usp=sharing
* You are good to go!

### Using License plate recognition
```
 %cd /content/drive/MyDrive/yolo_Car/yolov7
!python detect_plate.py --weights /content/drive/MyDrive/yolo_Car/plate/weights/best.pt --conf 0.1 --source /content/drive/MyDrive/yolo_Car/Plate.mp4 --video_frame 10
``` 

### Using line crossing car counter plate 
 ```  
%cd /content/drive/MyDrive/yolo_Car/yolov7
!python detect_cross.py --weights "yolov7.pt" --conf 0.1 --source /content/drive/MyDrive/yolo_Car/traf.mp4 --video_frame 2
  ``` 
### References
https://github.com/WongKinYiu/yolov7
https://github.com/xinntao/Real-ESRGAN
