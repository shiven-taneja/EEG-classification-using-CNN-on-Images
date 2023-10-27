# <center> EEG Classification Using CNN on Images</center>
**<center>Predicting whether a student understood a video based on their EEG signals</center>**

*Author: Shiven Taneja*

*Date: 26th August 2023*


# Project Overview

I have been completing the [Practical Deep Learning For Coders](https://course.fast.ai/) course by [Fast.AI](https://fast.ai). In the first two lessons, we learn about using the fastai library to classify images to a category through CNN. The example they used was classifying dogs vs. cats but on their forum there was a discussion on classifying time series data by creating images and using a CNN classifier on that. One person used this to classify [olive oils by means of a polar coordinate transformation called the Gramian Angular Field](https://forums.fast.ai/t/share-your-work-here/27676/366). This had an accuracy of 93.3%.

This inspired me to try the same technique on EEG classification. In order to do this, I used the EEG dataset [EEG data / Distance Learning ](https://www.kaggle.com/datasets/madyanomar/eeg-data-distance-learning-environment). The data from that dataset was taken using the [Emotiv Epox X ](https://www.emotiv.com/epoc-x/)14 channel headset. The data tracked the brainwaves of participants as they watched a video and classified them as either understanding or not understanding the content. In order ot classify this data, I transformed this data into a MNE data format and then created an image of it using the ssqueezepy imshow function. I saved these files and used a CNN to classify the images. During training, **my model worked with an accuracy of84.3%**. 

This project allowed me to combine what I learnt from the practical deep learning course, what I have learnt in my degree from UofT in Cognitive and Computer Science as well as what I have learnt as a Neurotech Consultant. The high accuracy rate shows that transforming EEG data into images and using this to classify them actually works!
