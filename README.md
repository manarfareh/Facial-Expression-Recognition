# Facial-Expression-Recognition

In this project, We are going to developa an image classification model to distinguish between seven emotions: joy, surprise, fear, anger, disgust, sadness and  neutral. The dataset used for this project is FER 2013 From Kaggle , consisting of images capturing diverse emotional expressions.

Facial Emotion Recognition:

Facial Emotion Recognition (FER) is the technology that analyses facial expressions from both static images and videos in order to reveal information on one’s emotional state. 

Data Exploration :

The data have been categorized into facial expression in to one of seven categories :
0=Neutral, 1=Happy, 2=Surprise, 3=Disgust, 4=Angry, 5=Sad, 6=Fear.
The training set consists of 28,709 examples. The test consists of 7178 examples.

Data preparation:

Images are preprocessed to enhance their suitability for model training. This includes resizing and normalization to ensure consistency in image dimensions and pixel values.

The dataset is divided into training, validation, and test sets. This division is essential to assess the model's performance on unseen data and prevent overfitting.

Creating the model:

CNN:
 is a regularized type of feed-forward neural network that learns feature engineering by itself via filters (or kernel) optimization.
-> CNNs use relatively little pre-processing compared to other image classification algorithms.

MobileNet:
MobileNets are based on a streamlined architecture that uses depth-wise separable convolutions to build light weight deep neural networks.

Loss History:

![alt text](https://github.com/manarfareh/Facial-Expression-Recognition/blob/main/DEMO/Loss%20History.png?raw=true)


Confusion Matrix:

![alt text](https://github.com/manarfareh/Facial-Expression-Recognition/blob/main/DEMO/Evaluation%20with%20MobileNet.png?raw=true)


Evaluation:

![alt text](https://github.com/manarfareh/Facial-Expression-Recognition/blob/main/DEMO/Evaluation.png?raw=true)
