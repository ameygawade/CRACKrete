# CRACKrete
 A Deep Learning-Based Image Classification Tool for Concrete Crack Detection

## Dataset: 

Kaggle: Surface Crack Detection
- https://www.kaggle.com/datasets/ahsanulislam/concrete-surface-image-filtered-with-match-filter/data

Each of the image is processed with match filter and Otsu thresholding method. The main purpose of this work is to enhance the binary classification accuracy and efficiency

The datasets contains black and white binary images of various concrete surfaces with and without crack. The image data are divided into two as negative (without crack) and positive (with crack) in separate folder for image classification. Each class has 20000 images with a total of 40000 images with 227 x 227 pixels with single channel. The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). High resolution images found out to have high variance in terms of surface finish and illumination condition. All the image data is preprocessed using MATLAB. The dataset was converted from RGB to Binary image with the help of OTSU thresholding method and Match filter. No data augmentation in terms of random rotation or flipping or tilting is applied.