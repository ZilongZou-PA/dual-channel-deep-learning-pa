# Denoising of photoacoustic signal based on reference-inputted convolutional neural network

## Description
This repository is the official implementation of paper "Enhancement of structural and functional photoacoustic imaging based on a reference-inputted convolutional neural network."

## Instructions

1. `data_train.mat` contains the training data. `test_y` and `train_y` represent the ground truth, while `test_X` and `train_X` consist of the concatenated detected PA signal and the environmental noise.
2. Run `dual-channel noise cancellation.ipynb`.
3. `f.mat` contains the PA signal and the environment noise data before denoising, and `y.mat` contains the PA signal after denoising.



