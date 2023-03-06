# Task: 
1. Take photos of your environment of two or more objects. (at least 100 instances between all objects) 

2. Annotate them on roboflow. 

3. Train a Faster RCNN model using detectron2

4. Train Yolov4/5/6/7/8 (only one of them of choice) the smallest size

5. Evaluate both models based on mAP and speed and size.

# 1. Taking photos
2 Objects' pictures were taken. 1. Pyramid, 2. Glasses
Pyramid image :

<img width="206" alt="image" src="https://user-images.githubusercontent.com/69463767/223180502-49216c29-225f-4e1d-82f7-10bffbac1ef2.png">

Glasses image:

<img width="202" alt="image" src="https://user-images.githubusercontent.com/69463767/223181025-6ee53a38-aa0f-4b0b-8ea6-57de52888d1f.png">

# 2. Annotation on roboflow
<img width="958" alt="image" src="https://user-images.githubusercontent.com/69463767/223181521-925eab2b-f2be-4899-815a-7c95e38913c8.png">


# 3. A Faster CNN using detectron2
<img width="620" alt="image" src="https://user-images.githubusercontent.com/69463767/223225085-7d9c0cc6-2c86-4ea8-aae1-02814ff0a261.png">


# 4. Yolov8 trained for 20 epochs
<img width="536" alt="image" src="https://user-images.githubusercontent.com/69463767/223225299-ce15866f-08b3-4630-9736-86e5bbb6fc74.png">

# 5. Evluation and comparison
### Mean Average Precision
- Faster RCNN: ~0.01%
- Yolov8: ~0.13%

### Speed:
Yolo is more speedier despite its size, and its speed has a number of advantages.
Yolo training takes 3 to 4 minutes for 24 epochs, but Faster RCNN (detectron2) takes more than an hour.

### Size:
Bigger RCNN model size: 805.5 Mb
The Yolov8 model size: 21.53 Mb
