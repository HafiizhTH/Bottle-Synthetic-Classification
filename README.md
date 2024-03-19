# Bottle-Synthetic-Classification
I made this project when I joined the advanced scholarship program from IDCamp 2023 in learning Machine Learning development at Dicoding Indonesia.

![image](https://github.com/HafiizhTH/Bottle-Synthetic-Classification/assets/96015981/7b4db522-e6c8-498e-855d-532601ac4a27) 

## Overview
The dataset I used is sourced from kaggle and contains synthetically generated images of bottles scattered around a random background.

![output](https://github.com/HafiizhTH/Bottle-Synthetic-Classification/assets/96015981/7750763c-ad3c-4ba5-b58a-c0dcf81bd935)

About | Description
:---|:---
Dataset | Bottles Synthetic Images [Click here](https://www.kaggle.com/datasets/vencerlanz09/bottle-synthetic-images-dataset/data).
Data All  | 25000 images.
Categories | Soda Bottle, Wine Bottle, Water Bottle, Plastic Bottle, Beer Bottles.
Data Training | 20000 Images.
Data Testing | 5000 Images.

The main folder contains 25000 Images divided in 5 categories each containing 5000 images with 512 X 512 RGB resolution and JPG file extension.

## Objective
This project requires pandas, matplotlib, seaborn, sklearn, tensorflow libraries. So, you may need to install these packages if you want to test it.

The process I did was as follows:
- Data Understanding
- Split Training and Test data
- Augmentation & ImageDataGenerator
- Modeling: Sequential Algorithm
- Evaluation
- Model to TF-Lite Converter

## Result
![accuracy](https://github.com/HafiizhTH/Bottle-Synthetic-Classification/assets/96015981/9c7aa4f3-bcca-433a-972c-eccf2006f4ea)

![loss](https://github.com/HafiizhTH/Bottle-Synthetic-Classification/assets/96015981/f8facf93-b0b1-4e05-a3fa-79381d9f0ac5)

I have obtained an accuracy of 0.92 which is quite good, so I can conclude that this model can work effectively by using LSTM in the model architecture. In addition, I used the Mean Absolute Error (MAE) scale as an evaluation metric.

