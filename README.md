**Brain-Tumour-Detection-using-YOLOv5**

**Background:** MRI denotes “Magnetic Resonance Imaging”. Finding the location of different kind of tumour separately from huge dataset is obviously a tuff work to do for the medical representatives. So, we proposed an algorithm based to YOLOv5 to find the location of the tumours and to know what kind of tumour is it. 

**Method:** First we used CNN base algorithm to find the presence of brain tumour in MRI images and got 99.74% accuracy. Then we tried to find the exact location of the tumour using YOLOv5 algorithm. YOLOv5(You Only Look Once) is a popular object detection algorithm  introduced by Glenn Jocher using the Pytorch framework. We have tried to change some of its parameter to enhance the accuracy and got 99.5% accuracy.We have labelled our own MRI dataset with two classification (Benign and Malignant Tumour) which is consist of 50 different kind of brain tumour MRI images.

**Result:** As we know in YOLO model, the mean average precision (mAP) is used to find the accuracy. The mAP compares the ground-truth bounding box to the detected box and returns a score. More high score means more accurate model in its detections. In our proposed model we get 99.5% accuracy which is better than the state of the result obtained so far.    

**Conclusion:** In this research we proposed an algorithm based on YOLOv5 that can help medical representative classify different tumours in less amount of time.
