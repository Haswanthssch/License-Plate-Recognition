# License-Plate-Recognition

This project focuses on License Plate Recognition (LPR), which involves two primary tasks: detecting the location of license plates in vehicle images and recognizing the alphanumeric characters on the plates.

## Problem Overview

The task involves working with two distinct datasets:

1. **Training Set 1**: 900 images containing vehicles with annotated bounding boxes around the license plates.
2. **Training Set 2**: 900 images containing only license plates, with annotations for the alphanumeric characters on each plate.
3. **Test Set**: 201 images with vehicles and license plates, where both detection and character recognition need to be performed.

The goal is to:
- Detect the license plates within the vehicle images.
- Recognize the alphanumeric characters on the detected license plates.

## Project Structure

```bash
├── data/
│   ├── train_set_1/           # Images of vehicles with annotated bounding boxes for license plates
│   ├── train_set_2/           # Images of license plates with annotated alphanumeric text
│   ├── test_set/              # Test images for license plate detection and recognition
│   ├── annotations/           # Annotation files containing bounding boxes and characters
├── src/
│   ├── preprocessing.py       # Data preprocessing scripts
│   ├── model.py               # Model building and training script
│   ├── inference.py           # Code for making predictions on the test set
├── notebooks/
│   ├── data_exploration.ipynb # Jupyter Notebook for data exploration and analysis
│   ├── model_training.ipynb   # Jupyter Notebook for model building and evaluation
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── LICENSE                    # Project license
