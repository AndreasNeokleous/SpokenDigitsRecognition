# Speech Recognition of Spoken Digits with CNN
The purpose of this project is to implement and train a Convolutional Neural Network so that is is able to classify spoken digits from 0 to 9.

# Dataset
Dataset: http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz

The dataset is a set of .wav files of people saying the digits 0 to 9. The files are resampled from 16000 to 8000 to reduce the dimensions
and then are transformed into spectrograms. A spectogram is the visual representation of the spectrum of frequencies of sound. The image is fed into the CNN for training.

# Requirements
Python 3.6, numpy, scipy, pandas, keras, sklearn, tensorflow-gpu, matplotlib

