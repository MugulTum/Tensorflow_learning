![image](https://github.com/MugulTum/Tensorflow_learning/assets/51419150/5e8780e1-9343-4c1f-af52-95477398d953)![image](https://github.com/MugulTum/Tensorflow_learning/assets/51419150/3b60e22a-c9b3-43c9-b7bd-fb6cd675e1d4)![image](https://github.com/MugulTum/Tensorflow_learning/assets/51419150/39aad976-813e-488d-9a22-68f93246b726)![image](https://github.com/MugulTum/Tensorflow_learning/assets/51419150/e61cd6cc-ff4b-45f8-b23a-7e98674ee1c1)![image](https://github.com/MugulTum/Tensorflow_learning/assets/51419150/4efd68a8-d086-4875-8e4a-7e92d52d8225)# Tensorflow_malaria
## Introduction 
Malaria is among the common diseases that kills millions of people annually 
In Sub-Saharan Africa, malaria has killed many people with majority being children below 5 years 
The malaria-causing parasites are carried by female anopheles mosquitoes 
## Malaria Detection
Traditionally, blood smear microscopy has been used to detect malaria and this approach is usually time-consuming
Early detection of malaria is crucial in administering medications that will reduce the likelihood of the patient succumbing to the disease
Because of the need for early detection, machine learning models have been developed to help with that 

## Malaria detection with machine learning 
Convolutional Neural network (CNN) is the approach being used to help in detecting the image classes 
In this project, the malaria dataset of the TensorFlow library is used to create a machine learning model to help in the detection of malaria parasites 
Malaria dataset contains 27,558 image 
The malaria dataset has two classes: Parasitized and Uninfected 
Before modelling, the data has to be preprocessed to ensure all images are of a standard size 
For images, the common preprocessing steps are resizing and normalizing 
The images in the dataset were resized to have a shape of 150 by 150 

## Model Training
The model was trained using the preprocessed data 
The data used for the training is the training dataset and then validated using the validation dataset 
Splitting of the data into training, validation and testing ensures the model does not overfit 
![Model performance](https://github.com/MugulTum/Tensorflow_learning/assets/51419150/86e470eb-63d6-4d1b-be51-39372aa93048)

The accuracy plot follows a similar trend like the model loss plot. 
After 2 epochs, the accuracy plot increases slightly to almost 100% while the validation accuracy is levelling off. 

## Model Testing
The next phase is testing the model using the unseen data 
When tested with the testing data, the model has a performance of 93.66%
This project was successful in developing a model using the TensorFlow library 





