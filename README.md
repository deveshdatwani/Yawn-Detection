# Yawn Detection 

### Introduction

Yawn can be an indicator of high fatigue levels. An application that detects if a person is yawning could be deployed at various platforms.

### Theory

This Python program uses the dlib library to detect shapes. The shape predictor algorithm implemented in the dlib library comes from Kazemi and Sullivan’s 2014 CVPR paper, One Millisecond Face Alignment with an Ensemble of Regression Trees. Feel free to read more about it.

The shape predictor 68 face landmarks is a pretained face detector that detects 68 landmarks on a face. They are numbered as shown below.

![]()

To detect if a person is yawning or not, we need to determine if the upper and lower lips are seperated by decent amount of pixels for a sufficient amount of time. A yawn generally lasts 2-3 seconds. This could give us the different between yawns and yelling/talking. We can further train a Neural Network with labelled images. But this project doesn't go into that.

The following code block shows the most important part of tha application. Rest everything is pretty standard.

![]()

### Installation and Launch (Linux)

Clone the git repository using the following command 

```
git clone https://github.com/deveshdatwani/Yawn-Detection.git
```

Run the yawn_detection.py script using

``` 
python3 Yawn_Detect.py
```
