
# Introduction
The repository contains the code files and dataset samples for the project of ENEL 645. The project is to use deep learning models to classify pipe segment’s state (“fluctuate”or “leak”). Calculating the location of the leak point is not included in the project. 

1)	“dataset_resized” folder contains all the data samples for this project. The raw pressure data for each sample are in a .csv file in the folders “fluctuate” and “leak”. The extracted features of skewness and kurtosis are saved in .csv files with prefix name “dataset_resized_”.
2)	“Convolutional_Neural_Network.ipynb” code file is to train a model based on Convolutional Neural Networks to do prediction.
3)	 “Fully Connected Neural Network.ipynb” code file is to train a model based on Fully Connected Neural Networks by using extracted features of skew and kurtosis to do prediction.
4)	“Extract Features of skew & kurtosis.ipynb” code file is to extract features of skew and kurtosis from input samples as the input of the Full Connected Neural Networks.
5)	“best_model_FCN.h5” file is the weights of the best models for Fully Connected Neural Networks.
6)	“best_model_CNN.h5” file is the weights of the best models for Convolutional Neural Networks. I trained it on TALC.

Team Number: 17

Team Member: Haixia Wu