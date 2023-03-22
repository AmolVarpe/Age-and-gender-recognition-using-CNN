# Age-and-gender-recognition-using-CNN
Project Descriptions-

Age detection is the process of automatically discerning the age of a person solely from a photo of their face.
Typically, you’ll see age detection implemented as a two-stage process:
Stage 1: Detect faces in the input image/video stream.
Stage 2: And apply the age detector algorithm to predict the age of the person.


code:-

This project code is divided  into 5 parts 
1.Config.py
2.Dataloader.py
3.Model.py
4.Train.py
5.Infernce.py

All of this file plays different roll in the project 

1.Config.py 

 All configurations of the project are have in this file such as required Library’s of python and input and output files locations.
This config file also consist of the different tuning parameters like EPOCHS , Alpha, ES_PATIENCE, ES_PATIENCE, LR_FACTOR.

2. Dataloader.py

Data loader files load the data from the given address and split it into train, test and validation.
This file also change the size of images and making into batches. 
Data loader file also count the total number classes in the data.

3.Model.py

Model file consist of main model which process the data.
In this file we using Resnet pretrain model and modify it accordingly after pre train model we using 3 interconnected layer.

4.Train.py

Train file only for the compile the file and train the data according to the model
Using the Adam optimizer 
This run the epoch and saving the best weights.


5.Inference.py

This inference file using for the apply pretrain weights and model on the real life photos and gets predictions accordingly of Age and Gender.





