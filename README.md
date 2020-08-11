# EEGPredict
This repository holds the code for the project "On an Emotionally Intelligence Responsive VR Environment" (website here: https://sites.google.com/nyu.edu/david-ugo-and-nyah-smith/home)

## Raw_EEG_Preprocess
This notebook preprocesses the raw DEAP dataset by extracting the "intense" moments of the trials.

## FFT_EEG_Preprocess
This notebook transforms the data gleaned from Raw_EEG_Preprocess into binned cells through Welch's method.

## NN_EEG_Predict_1
This notebook uses the data from FFT_EEG_Preprocess to train a neural network model to predict valence.

## KNN_EEG_Predict
This notebook uses the data from FFT_EEG_Preprocess to train a kNN model to uderstand the importance of certain channels in emotion.
