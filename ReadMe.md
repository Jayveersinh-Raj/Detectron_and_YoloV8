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

- confusion matrix
<img width="255" alt="image" src="https://user-images.githubusercontent.com/69463767/223226969-3968da55-f3da-4813-ac21-16589d2d28cd.png">

- F1 curve
<img width="298" alt="image" src="https://user-images.githubusercontent.com/69463767/223227062-e4bf5401-c43e-40b4-8082-15ca279360dc.png">

- PR curve
<img width="287" alt="image" src="https://user-images.githubusercontent.com/69463767/223227274-6336855b-41f4-4d25-8d5e-dbd8905cd3c8.png">

- P curve
<img width="291" alt="image" src="https://user-images.githubusercontent.com/69463767/223227362-23cc644a-14fc-4fee-b219-a1fe8c4b7844.png">

- R curve
<img width="294" alt="image" src="https://user-images.githubusercontent.com/69463767/223227446-d356d4b8-8ec1-4528-98de-34a0d4b0baa7.png">




# 5. Evaluation and comparison
### Mean Average Precision
- Faster RCNN: ~0.01%
- Yolov8: ~0.13%

### Speed:
Yolo is more speedier despite its size, and its speed has a number of advantages.
Yolo training takes 3 to 4 minutes for 24 epochs, but Faster RCNN (detectron2) takes more than an hour.

### Size:
- Bigger RCNN model size: 805.5 Mb
- The Yolov8 model size: 21.53 Mb


# References
1. https://docs.roboflow.com

2. https://blog.roboflow.com/how-to-train-yolov8-on-a-custom-dataset/

3. https://blog.roboflow.com/how-to-train-detectron2/

4. https://blog.roboflow.com/how-to-train-detectron2/#using-your-own-data-with-detectron2

# LINK TO THE COLAB: [Link](https://colab.research.google.com/drive/1xPn9YwrgVY1zSOBuradahRpXz_IvHubZ#scrollTo=VBGJm5QNmgxq)
