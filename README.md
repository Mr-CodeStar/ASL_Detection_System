# ASL Detection System Using Convolutional Neural Networks (CNN)

## 📋 Overview
This project focuses on building a deep learning model using Convolutional Neural Networks (CNN) to detect asl.
By leveraging a labeled dataset of hand sign images, the model learns to identify and categorize different alphabets based on their visual features.

## 🌟 Features
- CNN Architecture: Includes multiple convolutional, pooling, and fully connected layers.
- Data Augmentation: Uses techniques like flipping, rotation, and zooming to enhance the model's generalization.
- Performance Metrics: Tracks accuracy, precision

In this programe the number of epochs used is only 12 but still i get pretty good result.

![The accuracy increased in a steady rate.](path/to/image)

## 📊 Results
| Accuracy         | Value |
|------------------|-------|
| Training         | 89%   |
| Validation       | 71%   |

I believe that with 18 or 20 epochs the accuracy may reach to >90%
I didn't so that much epochs because in kaggle for some reason i am not able to use the TPU vm v3-8, and yesterday it took 4 and half hour to just complete 11/20. in GPU P100.
