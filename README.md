# Humane-pose-classification
# Topic: Human pose classification/estimation

Group Members:
- Nurlan Sultan
- Adilkhan Nurmiyashev
- Byegarys Byekbolat

Group: IT-2202

# Introduction:

Human pose estimation is a crucial task in computer vision that involves predicting the spatial positions of body joints in an image or video. This technology plays a pivotal role in various applications, including augmented reality, gesture recognition, sports analysis, and human-computer interaction.

![Picture1](https://github.com/bell1ssimo/Humane-pose-classification/assets/151810267/4d1d87be-e760-4de8-96e8-2053d504f80d)

# Problem:

The complexity of human pose estimation arises from the diverse range of poses, variations in lighting conditions, occlusions, and the inherent challenges in capturing the intricate details of the human body.

# Literature Review:

The accurate estimation of human body poses from images and videos is a fundamental task in computer vision and has significant applications in various domains, including action recognition, human-computer interaction, and virtual reality. Over the years, several approaches and methods have been proposed to address the human pose estimation problem.
Randomized Decision Forests: Machine learning-based approaches gained prominence with the use of randomized decision forests. These methods, such as the one proposed by Shotton et al., focused on learning the relationship between image features and body joint locations. While these approaches demonstrated improved efficiency, their performance was often limited in capturing intricate pose variations.
OpenPose, developed by Cao et al., is a widely adopted and versatile human pose estimation framework. It employs a multi-stage pipeline, combining both convolutional and recurrent neural networks, to estimate key points and their interconnections accurately. The framework supports real-time pose estimation with applications in multiple domains.


# Current work:

In our project, we used CNN model and our own dataset using images taken from the Internet. At the moment, our work allows us to determine whether a person is in a sitting or standing position by highlighting key points on the human body with dots implementing opencv. We trained our model based on the key points of shoulders, knees, elbows, etc extracted from the opencv.

# Data and Methods:

We couldn’t find suitable dataset where the poses are labeled with names, so we collected our own small dataset (also we made rotating, scaling, flipping of img to increase dataset and accuracy of the model)
We used CNN model, our model defines whether the person in the image is standing or sitting  by implementing opencv to detect keypoints on the body
Trained the model by keypoints from images processed by opencv. So, the model works with keypoints, not images.
![Picture2](https://github.com/bell1ssimo/Humane-pose-classification/assets/151810267/2e3fd3ab-33de-413f-b276-8f8c10fdc41a)

CNN stands for Convolutional Neural Network, and it is a type of deep neural network commonly used in machine learning for tasks related to computer vision.
It is particularly effective in image recognition, classification, and other visual tasks due to their ability to automatically learn hierarchical representations from the input data.
Key components of a CNN include:
Convolutional Layers: These layers apply convolution operations to the input data, using filters or kernels to extract features from the input. Convolutional operations help the network recognize patterns and spatial hierarchies in the data.
Pooling (Subsampling) Layers: Pooling layers downsample the spatial dimensions of the input, reducing the amount of computation and preserving the important features. Common pooling operations include max pooling and average pooling.
Activation Functions: Non-linear activation functions, such as ReLU (Rectified Linear Unit), are applied to the output of convolutional and pooling layers to introduce non-linearity and enable the network to learn complex relationships in the data.
Fully Connected Layers: These layers connect every neuron to every neuron in the previous and subsequent layers, allowing the network to make decisions based on the high-level features learned in earlier layers.


OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. Being an Apache 2 licensed product, OpenCV makes it easy for businesses to utilize and modify the code.


# Result:

Model accuracy

![Picture3](https://github.com/bell1ssimo/Humane-pose-classification/assets/151810267/b5df9148-0148-4286-828b-e4b6a06403a7)
![Picture4](https://github.com/bell1ssimo/Humane-pose-classification/assets/151810267/a24d0722-cdde-4ce7-a9fa-2397cf271759)
![Picture5](https://github.com/bell1ssimo/Humane-pose-classification/assets/151810267/56d690f2-a4c2-482d-92d5-ac2be5adb524)




# Discussion:

The main problem of our project was the working process with the opencv and the training model with the outputs of key points from opencv.
The next step of the project would be making it working with the videos/webcams.

# Links(sources):

Dataset that we collected: https://drive.google.com/drive/folders/1oMNxLk2BxM7VtyfEp-rn058NpzfCTSef?usp=sharing

Images for testing the model: https://drive.google.com/drive/folders/1d_IFMnZIn72u7tpr6kn7ZUJc6Cq9t3Em?usp=sharing

# Link to youtube video:
https://youtu.be/SbByNUsxohc
