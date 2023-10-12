# Emotion_Detection-Using-Yolov5
## Overview
Emotion detection typically categorizes emotions into basic or complex categories such as happiness, sadness, anger, fear, surprise, disgust, and sometimes more nuanced emotions like confusion, excitement, or trust. These categories can vary depending on the specific application and dataset.

### 📁 Dataset Used : Emotion Detection: https://universe.roboflow.com/school-ytrhi/emotion-zjj8h
**The dataset consists of two classes:**
0, 1, 2, 3, 4, sad

![image](https://github.com/Tanwar-12/Emotion_Detection-Using-Yolov5/assets/110081008/46a34086-9be8-453b-b0bd-70ecd43d5cd9)
# Workflow:
  ## Data Preparation:
  * Total 1313 images for training and 144 images for validation present in 26classes.
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
  [train folders](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/69b19a8e-2f81-4d9b-a762-ffa73ac59be1)
## Steps to use Yolov5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:
 1. Training and Validation file path
 2. Number of classes and Class names.

  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Train model around 600 epochs .
* Visualise the training metrics with the help of tensorboard.

 ## Testing Images Using Test Data
 ![image](https://github.com/Tanwar-12/Emotion_Detection-Using-Yolov5/assets/110081008/c448a90f-1576-4ee1-be43-6cf5bcfd80e9)

 ![image](https://github.com/Tanwar-12/Emotion_Detection-Using-Yolov5/assets/110081008/71c2a5de-7e97-4389-9add-2a454613c2d7)

## Testing Video Demo:


https://github.com/Tanwar-12/Emotion_Detection-Using-Yolov5/assets/110081008/7bacb8a1-365f-4714-9580-b2369530851c


