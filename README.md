# Age_Guesser
Abstract:
In recent years, Convolutional Neural Network(CNN) is popular and widely used in computer vision tasks, and many related applications and datasets are proposeA. Datasets
1.The OUI-Audience Face Image Project
Consists of 26580 photos.
the images were labeled in groups and placed in different folders by the age ranges: 0-2, 4-6, 8-13, 15-20, 25-32, 38-43, 48-53, 60+.d. In this project, I aimed to propose an application that predicts human ages, which is interesting and useful in the real world. I used 3 human face datasets to train the convolutional neural network models that predicted human ages based on the face images. In addition, I improved the model architecture and evaluated accuracies between different datasets and model architectures. Lastly, I used the OpenCV package to implement the real-time age-guesser application. 
Methods:
A. Datasets
1.The OUI-Audience Face Image Project
Consists of 26580 photos.
the images were labeled in groups by the age ranges: 0-2, 4-6, 8-13, 15-20, 25-32, 38-43, 48-53, 60+.
2. UTKFace
Consists of 20k+ face images in the wild, which are labelled by age, gender, and ethnicity.
3.Facial Age
10k+ images which were labelled by age.
B. Data Preprocessing
1. Label ages in group
Since the OUI-Adience Face Image Project labeled ages in groups, we labeled the ages in group in others datasets for the consistency.
2. Balances the datasets by the age labels
Regulate the distribution ratio of each label by sampling the fixed number of images in each class.
C. Model Architectures
1. The baseline of the model
2. The improved model







