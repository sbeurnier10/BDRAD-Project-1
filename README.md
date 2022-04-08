# CV-Breast-Tumor-Detection
Using Mammogram Images to Diagnose Breast Tumors

# Overall Objective
Create a basic 2D convolutional neural network algorithm to predict breast density (classification problem)

# Steps
For Helper.ipynb
1) Wrote a function that can load DICOM or PNG file and then convert them to user specified image size (ex: 299 x 299 or 229x229) numpy files. 
2) Combined the numpy file with breast density information (binary) to create numpyZ files.

For PyTorch ResNet.ipynb
3) Created a basic ResNet architecture to train on breast denseness.
4) Performed predictions with the algorithm on the testing set.
5) Provided confusion matrix and ROC curve. Performed DeLong test and confidence interval around the ROC curve using bootstrapping

