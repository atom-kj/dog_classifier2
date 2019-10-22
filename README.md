
## Project Description

The purpose of the project is to use a convolutional neural network to identify dog breeds from the pictures. It classify the picture image is either human or dog and then prediction of dog breed is performed. If the picture is classified as human. It shows which dog breed is the most resemble that human. 

### Libraries used

* numpy 1.12.0
* scikit-learn 0.18.1
* Keras 2.0.2
* tensorflow 1.0.0
* jpykernel 4.6.1
* pillow 4.0.0
* tqdm 4.11.2
* scipy 0.18.1
* matplotlib 2.0.0
* h5py 2.6.0
* pencv-python 3.2.0.6

### Files in Repository

* bottleneck_features
* haarcascades
* image # picture directory for notebook
* pictures # picture directory for test identification 
* requirements # requirements directory
* saved_models   #saved model data are contained
* CODEOWNERS
* dog_app.ipynb # notebook for analysis
* extract_bottleneck_features.py
* LICENSE.txt # udacity license document
* README.md

## Motivation
For making a technical blog post to test CNN capability for dog classifier
Blog: https://medium.com/@atomic.fbr.kaji/showcase-of-dog-image-classifier-7797414d4a0c


## A summary of results
The tuned algorithm peformance of the classification for the test dataset of dog image was 80.2632 % instead of 39.7129% of original CNN momdel. For the technically difficult cases, it does not work so well.
