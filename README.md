# CarPlateDetector
A deep learing model that detects the plate license of cars.

## What did I do ?
1.  Loaded a pretrained model (FasterRCNN).
2.  Changed the number of output classes to fit our problem (Transfer learning).
3.  Trained the model on the new dataset.

## DataSet
I used a public DataSet provided by [Zindi](https://zindi.africa/), containing 900 images with the coordinates of the bounding box.

## Prediction example
![image](https://github.com/younes38/CarPlateDetector/blob/master/images/download.png)  
Even if I trained the model on Tunisian Plate licenses, it works well on cars from other countries.


## Why this projec ?
After finishing the Deep Learning Specialization (Coursera - by Andrew Ng),  it's time to apply what I've learnt in real world problems so I started with a computer vision problem.


## TODO
-  improve the model so that it can detect multiple license plates.
-  Recognise the code in the detected license plate.
