# CSE465 Project: Flame-Smoke-Detection
## Problem
A classification problem to classify images containing flame and smoke from the image dataset.
- Required data was collected form Kaggle
- The dataset contains 3000 images 
- 90% of them were used to train the model and the rest 10% were used to test and validate the model
- The image data was divided into smaller batches and batch normalization was used as a dataset augmentation technique

## Solution
Primarily approached the problem with custom CNN architecture.
Then applied various pre-trained models of different architectures to find the best solution with maximum accuracy. <br>
Different Approaches:
- Custom CNN
- ALEXNET
- RESTNET
- VGG16
- ZFNET


## Accuracy after each epoch
![image](https://user-images.githubusercontent.com/25506807/133051824-15b0df65-3732-4365-95a7-9692aa6bba20.png)

## Accuracy, Recall, Precision
![image](https://user-images.githubusercontent.com/25506807/133052072-58bcc78a-10e7-4413-93a8-ce78c10dd6a3.png)

## Confusion Matrix
![image](https://user-images.githubusercontent.com/25506807/133051904-40a877d1-dc10-4a66-8a3d-9af91f597553.png)


