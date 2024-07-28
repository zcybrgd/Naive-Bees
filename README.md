# Naïve Bees
## first step: 
# Image Loading and Processing
- loading the bumble and honey bees images and manipulating them using the PIL library
- making a pipeline with converting the loaded images to grayscale to eventually save them

## libraries used=  PIL, numpy, matplotlib
## second step: 
# Predict Species from Images
- building a binary classifier using supervised learning to detect honey bees and bumble bees in images.
- data visualisation using Matplotlib
- Generate the row of features after flattening them into a single row
- split into train and test data
- Scaling the data using StandardScaler
- Performing dimension reduction using PCA


## libraries used+= sklearn, skimage
## third step: 
# Deep Learning with Images
- Building a Convolutional Neural Network to binary classify the bees in the database
- Normalization of the data using the standard scaler
- Visualizing the accuracy and loss metrics for the model on training, testing and evaluation data
- Loading the model and re-using it in different emplacements and visualizing the history of the model

## libraries used+= keras
