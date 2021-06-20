# Mitigate-the-bias-in-binary-classification-on-Labeled-Faces-in-the-Wild-dataset

dataset : [LFW dataset](http://vis-www.cs.umass.edu/lfw/)

This project contains the binary classification for a person wearing 'sunglasses'/'Eyeglasses' in the dataset. The dataset split into two part 65% training and 35% of total dataset as testing.
For the performing classfication , use dense layer model : [ 128 -- 128 -- 128 -- 64 -- 1 ] and MSE loss function and analyze the bias in the system with three different metrics.

Mitigation of bias done using DATA method (Training using more data): We may use more data for training from that 35% data. Report the accuracy after mitigation and compare it with previous
classification results. 

And second is ALGORITHMIC method: Alter loss function to incorporate more challenges. Use a multi-tasking approach to achieve  aim.Report the accuracy after mitigation and
compare it with previous classification results.
