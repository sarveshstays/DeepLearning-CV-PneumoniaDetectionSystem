# DeepLearning-CV-PneumoniaDetectionSystem
Build a pneumonia detection system, to locate the position of inflammation in an image

Dataset - https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/overview/acknowledgements

# Projet Description

Tissues with sparse material, such as lungs which are full of air, do not absorb the X-rays and
appear black in the image. Dense tissues such as bones absorb X-rays and appear white in the
image.
While we are theoretically detecting “lung opacities”, there are lung opacities that are not
pneumonia related.
In the data, some of these are labeled “Not Normal No Lung Opacity”.
This extra third class indicates that while pneumonia was determined not to be present, there
was nonetheless some type of abnormality on the image and oftentimes this finding may mimic
the appearance of true pneumonia.
Dicom original images:- Medical images are stored in a special format called DICOM files
(*.dcm). They contain a combination of header metadata as well as underlying raw image
arrays for pixel data.


# Milestone 1: Pre-Processing, Data Visualisation, EDA and Model
Building
● Exploring the given Data files, classes and images of different classes.
● Dealing with missing values
● Visualisation of different classes
● Analysis from the visualisation of different classes.
● Building a pneumonia detection model starting from basic CNN and then improving
upon it.
● Train the model
To deal with large training time, save the weights so that you can use them when
training the model for the second time without starting from scratch.

# Milestone 2: Test the Model, Fine-tuning and Repeat
● Test the model and report as per evaluation metrics
● Try different models
● Set different hyper parameters, by trying different optimizers, loss functions, epochs,
learning rate, batch size, checkpointing, early stopping etc..for these models to finetune them
● Report evaluation metrics for these models along with your observation on how
changing different hyper parameters leads to change in the final evaluation metric


# Objective

● Learn to how to do build an Object Detection Model
● Use transfer learning to fine-tune a model.
● Learn to set the optimizers, loss functions, epochs, learning rate, batch size,
checkpointing, early stopping etc.
● Read different research papers of given domain to obtain the knowledge of
advanced models for the given problem.
