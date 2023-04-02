# EMOTION-RECOGNITION
  Emotion recognition using AI is a technology that involves using machine learning algorithms to analyze and identify human emotions from various sources such as facial expressions, voice tone, and body language.

  This project will present two methods for emotion detection using both Deep Learning and Machine Learning

## First Method: Real time Emotion detection Using DeepFace:

  DeepFace is a deep learning facial recognition algorithm developed by Facebook's AI research team.
In this project we will do a Real-time emotion detection using DeepFace to detect emotions in live video streams or video frames in real-time. 

__requirements__

Libraries:

  OpenCV

  DeepFace a library built on top of the Keras.
    
  matplotlib
    
haarcascade_frontalface_default.xml file, can be found in ( https://github.com/kipr/opencv/tree/master/data/haarcascades )

feel free to run the notebook __Real time Emotion recognition using DeepFace__ and test it in your computer


## Second method: AN End-to-End Emotion Recognition Estimator based on body language.


### __training and deploying a Gesture-based large language model based on Dynamic Time Warping and logistic regression.__

__This project includes an end-to-end workflow that covers data collection, pre-processing, feature extraction, DTW-based pattern matching, and emotion classification. The resulting model can be deployed in real-world settings, such as human-robot interaction or virtual reality scenarios, to recognize emotions expressed through gestures in real-time.__

__DTW (Dynamic Time Warping)__ is a pattern recognition algorithm that measures the similarity between two time-series data, such as body joint signals representing the expression of emotions during different gestures. DTW allows for a flexible comparison between the recorded signals and pre-defined emotional templates, even when the signals vary in length, speed, and temporal alignment. The algorithm works by creating a distance matrix that compares all possible combinations of corresponding points in the two sequences, and then finding the optimal warping path that minimizes the cumulative distance between the corresponding points. DTW is particularly effective in recognizing temporal patterns in signals, and can help identify the emotion expressed through the recorded gesture. DTW can be applied to a wide range of body joint signals obtained from wearable sensors or motion capture systems, making it a versatile tool for emotion recognition in gesturing.

the following notebook __Emotion Recognition with ML and DTW.ipynb__ explain how it is done step by step

the deploying time was around 2 secondes per 1 captured video which makes it very promising for a real time deployement even competing with deepl learning models 
