# German-Traffic-Sign-Detction

Detect The German Traffic Sign Using YoloV5

# DATA COLLECTION:
**Data Collected form Rubixe For Educational Internship**

# TASK: Object Detection

# DATA INFORMATION:
* Total 4290 traffic sign images are present in 39 classes Each class contain 110 images
* Split data with the help of splitfolder library.
* 88 Images for training and 22 images for validation
* Create bounding boxes with the help of label-img tool and makesense.ai website

# German Traffic Signs


![image](https://user-images.githubusercontent.com/101791322/209359733-a6ef893c-ed75-4d3e-aafa-29c5551d8e3c.png)


# DATA PREPRATION:
*	Prepare folder structure that can be accept by YoloV5.
* Total 3438 images for training and 857 images for validation present in 39 classes.
* Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.

# STEPS TO USE YOLOV5
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights

## STEPS BEFORE TRAINING CUSTOM DATASET:
1. Go to yolov5/data/
2. Open coco128.yaml
3. Edit the following inside it:


     A. Training and Validation file path

     B. Number of classes and Class names.

# TRAINING YOLOV5 MODEL
* Set images size 128 with batch of 8
* Train model on 50 epochs 
* Gives the data file path as well as give pre-trained weights path.

**VISUALISE THE TRAINING METRICS WITH THE HELP OF TENSORBOARD**

# AFTER TRAINING THE MODEL 


![image](https://user-images.githubusercontent.com/101791322/209360083-d54ea901-abbc-413d-ac55-3877477a8656.png)


# VALIDATION IMAGES PREDICTION:

![image](https://user-images.githubusercontent.com/101791322/209360211-2a2716b6-4357-4255-ac11-97c49a95e654.png)


# PREDICTED IMAGES: 

![image](https://user-images.githubusercontent.com/101791322/209360263-7da472b9-8f8f-4d35-ad06-cd4dc4c5823a.png)


![image](https://user-images.githubusercontent.com/101791322/209360279-535ddd92-83d8-44ba-b9b6-d194afe71a8a.png)


# CHALLENGES FACED:
*	Facing problem to understand the business case.
*	challenge faced in bounding boxes creation
*	Assign same no for all classes
*	Made mistake in yolov5 folder structure
*	Take lots of time to create bounding boxes

# WHAT WE LEARN:
*	Convert classification task to object detection to improve skill in object detection
*	Understand the YoloV5 folder structure as well as learn label-img tool.
*	Learn pytorch library.






