# Music Genre Classification

## Objective : 
  To Classify music into various genres using Deep Learning

## Dataset Used :
  For this problem, I have used 2 different datasets : [Free Music Archive (FMA)](https://freemusicarchive.org/) and the [GTZAN Dataset](http://marsyas.info/downloads/datasets.html).
  FMA library is an interactive library of high-quality,legal audio downloads. For this problem, I have used a dump of
  this library which is available [here](https://github.com/mdeff/fma). The d ataset comes with different sizes :
  1. fma_small : 8,000 tracks of 30s, 8 balanced genres(7.2 GiB)
  2. fma_medium : 25,000 tracks of 30s, 16 unbalanced genres (22 GiB)
  3. fma_large : 106,574 tracks of 30s, 161 unbalanced genres (93 GiB)
  4. fma_full : 106,574 untrimmed tracks, 161 unbalanced genres (879 GiB)
  
  For this project I have used the FMA medium Dataset. The GTZAN dataset consists of 1000 audio tracks each 30 seconds long. 
  It contains 10 genres, each represented by 100 tracks. The tracks are all 22050Hz Mono 16-bit audio files in .wav format.

## Feature Extraction from Audio Signals : 
  For this project, I have used python's librosa library to extract both Spectral and Rhythm features from the audio signals.

## Modelling :
  Different models used for this project are : Simple Neural Networks, Convolutional Neural Networks, Uni-directional LSTM and Bi-directional LSTM
  
## Model Evaluation :
  The Dataset was split into Train and Test Dataset with 80% of data being used for Training and 20% of data for testing.
  Metric used for model evaluation is Accuracy.
