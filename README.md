# SpeechMNIST
### A Lip-Reading Dataset for Visual Speech Recognition
This repository hosts the new SpeechMNIST dataset for benchmarking visual speech detection. 
## Overview
SpeechMNIST has the following spezifications:
- consists of 6080 datapoints in 10 classes corrsponding to the numbers zero to nine
- each datapoint has a resolution of 224x224 pixels
- each datapoint is a video with the length of 1.5 seconds with the target word in it
- the distribution of classes is evenly distributed
### example

![datapoint with label 2](https://github.com/lohikaeaerme/SpeechMNIST/assets/35666743/faa70961-ec16-44bc-8437-cb88175039c4)


## Preparing
To use this dataset please use the `preparation.py` file to extract the labels into a csv file which can be used for training. 
If you want to use your own pipeline the data is sorted in folders by participants. Each folder has files named number.number_label, so you can also extract the labels by yourself.
