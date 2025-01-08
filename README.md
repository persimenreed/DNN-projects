# DNN-projects
Some deep neural network projects corresponding to the course IKT450

## KNN
This project implements the K-Nearest Neihbours (KNN) algorithm from scratch. The program is used to classify whether a patient has diabetes or not.    
![KNN-metrics](https://github.com/user-attachments/assets/7a8ad6c2-66a8-4d36-9d2e-a653651e2db8)

## MLP
This project implements multilayer perceptrons in two ways, both from scratch and using a high level library. When implemented from scratch, backpropagation and weight updates has to be manually calculated.
![MLP](https://github.com/user-attachments/assets/6e95c71d-1729-49cb-a1d5-e622935a265c)

## CNN
A convolutional neural network (CNN) is used to classify which food is on the picture. The model managed almost 60% on this small sample, but got an score of around 50% test accuracy, which is not too bad, given the 11 different food categories.
![food1](https://github.com/user-attachments/assets/a25ab702-9e24-4ff9-8461-d331483916e4)
![food2](https://github.com/user-attachments/assets/013870c9-8781-4af9-a1f9-536a4ce66d56)


## Object Detection
This project detects ballons using object detection. The following tutorial was used for this project:    
https://geekyrakshit.dev/geekyrakshit-blog/computervision/deeplearning/segmentation/objectdetction/neuralnetwork/instancesegmentation/convolution/detectron/maskrcnn/python/pytorch/2020/04/13/detectron-mask-rcnn.html    
![balloon](https://github.com/user-attachments/assets/8e1c609d-2cee-4e15-9ed7-84dff93b4f69)

## Chatbot
In this project a chatbot was implemented in two ways, both as a classifier, and as a generator. The results were not paticularly good, but I'll leave the project for people to see.    
Generator:
![Generator](https://github.com/user-attachments/assets/36329937-0f22-4ebf-840d-53236d8cb9c6)    
Classifier:
![Classifier](https://github.com/user-attachments/assets/1326bd23-0bca-463a-a0e4-ac7cbc56d13d)

## Noise removal
This project uses the same dataset as the CNN project, where a timestamp was added to the images of food, and the goal was to remove the noise. Our best result came from the autoencoder, where an implementation using a Gnerative Adversarial Network (GAN) and a diffusion model did not produce any good results
![AE](https://github.com/user-attachments/assets/0d7219d0-07b5-4ead-b47b-51890b1126fc)

















