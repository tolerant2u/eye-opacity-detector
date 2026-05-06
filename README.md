# Eye Opacity Detector

A program for automatic analysis of corneal opacity in eye images.

This project was developed as part of a computer science research project.

## Features

* Segmentation of the corneal opacity area
* Eye image analysis
* Calculation of the affected area
* Result visualization

## Technologies Used

* Python
* PyTorch
* OpenCV
* Tkinter

## Project Structure

```text
scripts/train_unet.py      U-Net model training
scripts/predict_image.py   Image analysis
scripts/main.py            Graphical user interface
scripts/mask_script.py     Image annotation
```

## Dataset

The dataset contains more than 500 images. It is not included in the repository due to its large size.
