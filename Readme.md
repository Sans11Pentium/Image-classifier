# Image Classification for a City Dog Show

## Description:
Your city is hosting a citywide dog show and you have volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information about their dog. The registration system tags the images based upon the biographical information.

Some people are planning on registering pets that aren’t actual dogs.

So we plan to identify whether the image has a dog or not. If yes, then identify the breed.

## Principal Objectives
- Correctly identify which pet images are of dogs (even if the breed is misclassified) and which pet images aren't of dogs.  
- Correctly classify the breed of dog, for the images that are of dogs.  
- Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve objectives 1 and 2.  

### In this project we had 2 main objectives:
1. Identifying which pet images are of dogs and which pet images aren't of dogs
2. Classifying the breeds of dogs, for the images that are of dogs

![alt text](/result.png)

Given our results, the "best" model architecture is VGG. It outperformed both of the other architectures when considering both objectives 1 and 2. You will notice that ResNet did classify dog breeds better than AlexNet, but only VGG and AlexNet were able to classify "dogs" and "not-a-dog" at 100% accuracy. The model VGG was the one that was able to classify "dogs" and "not-a-dog" with 100% accuracy and had the best performance regarding breed classification with 93.3% accuracy.