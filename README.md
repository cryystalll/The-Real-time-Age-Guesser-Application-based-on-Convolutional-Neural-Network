# The Real time Age Guesser Application based on Convolutional Neural Network
## Abstract:
```
In recent years, Convolutional Neural Network(CNN) is popular and widely used in computer vision tasks, and many related applications and datasets are proposed. 
I aimed to propose an application that predicts human ages, which is interesting and useful in the real world. 
I used 3 human face datasets to train the convolutional neural network models that predicted human ages based on the face images. 
In addition, I improved the model architecture and evaluated accuracies between different datasets and model architectures.
Lastly, I used the OpenCV package to implement the real-time age-guesser application.
```
## Age Guesser Application With OpenCV
```
I used the OpenCV package to build the real-time age guesser application. 
Firstly, I used the VideoCapture in OpenCV to capture frames from the webcam in real-time. 
Secondly, I used the face detection model provided by OpenCV to get the bounding boxes of faces. 
Note that the detection model can detect multiple faces in a single frame, thus, I may get multiple bounding boxes. 
Then, I cropped the face images in bounding boxes from the frame and resized the face images to the input size of our age guesser model.
Lastly, I used the model to predict the ages of face images and showed the predicted ages on the screen.
```
## Predicting face accurately
```
* In most of the test cases, the model could predict human ages accurately
```
<div align=center><img src="/img/face1.png" alt="Cover" width="60%"/></div>

## Predicting multiple faces’ ages in a frame
<div align=center><img src="/img/face2.png" alt="Cover" width="30%"/></div>

## Get start!
```
* 1.Get a frame from the webcam
* 2.Use provided face detection model to get the bounding box of face.
* 3.Crop and resize the face image from the frame.
* 4.Use the model to predict the age.
```
<div align=center><img src="/img/start.png" alt="Cover" width="70%"/></div>

## Methods:
## A. Datasets
* 1. The OUI-Audience Face Image Project
```
Consists of 26580 photos.
the images were labeled in groups by the age ranges: 0-2, 4-6, 8-13, 15-20, 25-32, 38-43, 48-53, 60+
```
* 2. UTKFace
```
Consists of 20k+ face images in the wild, which are labelled by age, gender, and ethnicity.
```
* 3. Facial Age
```
10k+ images which were labelled by age.
```
## B. Data Preprocessing
* 1. Label ages in group
```
Since the OUI-Adience Face Image Project labeled ages in groups, we labeled the ages in group in others datasets for the consistency.
```
* 2. Balances the datasets by the age labels
```
Regulate the distribution ratio of each label by sampling the fixed number of images in each class.
```
## C. Model Architectures
```
The baseline of the model
```
<div align=center><img src="/img/model1.png" alt="Cover" width="50%"/></div>

```
The improved model
```
<div align=center><img src="/img/model2.png" alt="Cover" width="50%"/></div>

## Results and Accuracies
<div align=center><img src="/img/accu2.png" alt="Cover" width="50%"/></div>







