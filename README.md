# Denoising of photoacoustic signal based on reference-inputted convolutional neural network

## Description

We propose a reference-inputted convolutional neural network (Ri-Net) for PA signal denoising . The input feature of the network comprises the spectra of the detected PA signal and the environment noise from another channel. Both signals are transformed into the frequency domain using the Fast Fourier Transform (FFT). The frequency spectrum of the two signals is then concatenated to form a comprehensive set of input features.

## Instructions

1. `data_train.mat` contains the training data. `test_y` and `train_y` represent the ground truth, while `test_X` and `train_X` consist of the concatenated detected PA signal and the environmental noise.
2. Run `dual-channel noise cancellation.ipynb`.
3. `f.mat` contains the PA signal and the environment noise data before denoising, and `y.mat` contains the PA signal after denoising.



