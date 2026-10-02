# Speech Command Classification using CNN

A speech classification project using a Convolutional Neural Network (CNN) trained from scratch.

## Dataset

* Google Speech Commands dataset
* 10 spoken commands
* 10,000 audio samples
* 8,000 training, 1,000 validation, 1,000 testing

## Approach

* Audio sampled at 16 kHz
* Extracted 40 MFCC features from each audio file
* Normalized the features
* Trained a CNN using PyTorch
* Model trained from scratch without a pretrained speech model

## Commands

`yes`, `no`, `up`, `down`, `left`, `right`, `on`, `off`, `stop`, `go`

## Evaluation

The model was evaluated on the held-out test set using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

Test Accuracy: **71%**

## Experiment

I tested two learning rates:

| Learning Rate | Test Accuracy |
| ------------- | ------------: |
| 0.001         |         71.0% |
| 0.0005        |         61.6% |

## Technologies

* Python
* PyTorch
* Librosa
* NumPy
* Scikit-learn
* Google Colab
