# Day-Night-Classifier
This repo contains code and models trained to classify day and night images.

### Requirements
- [numpy](https://pypi.org/project/numpy/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [OpenCV 3](https://pypi.org/project/opencv-python/3.4.9.31/)

### Dataset
The data for this project was scraped from [Pexels website](https://www.pexels.com/) using the [Download all images](https://addons.mozilla.org/en-US/firefox/addon/save-all-images-webextension/) extension for Mozilla Firefox.

The training set contains approximately 1000 images and validation set contains 200 images. An additional data cleaning phase was done manually to avoid noisy labels.

### Models
- Baseline model - Basic model that uses average brightness from Value channel of HSV image as threshold to classify image. Achieves an accuracy of 88.5% on the validation set.

### Files
- [Day-Night-Classifier.ipynb](https://github.com/amolmzope/Day-Night-Classifier/blob/main/Day%26Night%20Classifier.ipynb) - Training of baseline model
