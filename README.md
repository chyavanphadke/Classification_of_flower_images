# Classification of flower images

Github Link: https://github.com/chyavanphadke/Classification_of_flower_images

Class: EE 258 Neural Networks - Fall 2021  

Under the Guidence of 
- Prof. Birsen Sirkeci

Project Team Members
- Chyavan Phadke
- Neh Patel
## Table of Contents  
[1. Motivation](#Motivation)  
[2. Python Packages](#Python-Packages)  
[3. Models Used](#Models-Used)  
[4. Code Files](#Code-Files)  
[5. Running the code](#Running-the-code)  
[6. Results](#Results)  

## Motivation
The goal is to classify five kinds of flowers
- Daisy
- Dandelion
- Rose
- Sunflower
- Tulip

The Dataset from Kaggle is used [Link](https://www.kaggle.com/alxmamaev/flowers-recognition)

## Python Packages

- numpy
- matplotlib
- splitfolders
- tensorflow
- zipfile
- keras

## Models Used
- There are five kinds of models used for this dataset
- The first model is built from scratch
- The second model is built by pre-trained model VGG19
- The third and fourth model is again built from scratch
- Finally a ResNet-50 Pretrained model is used

## Code Files
- ### There are three python files
  #### First_Code_Models_Comparision.ipynb
  - In this part of the code we are computing four different models and their performance is plotted together

  #### Second_Code_Best_Model_and_improvement.ipynb
  - In this part of the code we have picked the best model and tried improving further

  #### Third_Code_towards_Extra_Credit.ipynb
  - This Code contains extension for the project [Towards Extra credit]

## Running the code
- All three codes has no dependency to run, as it will download the dataset and install the required libraries itself
- Google collab is suggested as it has GPUs so the computation will be faster.

  - In Google collab: then runtime > Run all
  - In Jupiter notebook: Run > Run All

## Results

| Model | Training Accuracy | Test Accuracy | F1-Score |
| :-: | :-: | :-: | :-: |
| Custom model 1 | 0.621 | 0.592 | 0.510 |
| VGG19_model | 0.521 | 0.485 | 0.410 |
| Custom model 2 | 0.875 | 0.810 | 0.832 |
| Custom model 3 | 0.612 | 0.589 | 0.602 |
| Custom model 4 | 0.784 | 0.712 | 0.699 |
| Custom model 5 | 0.910 | 0.839 | 0.901 |
| Custom model 6 | 0.972 | 0.956 | 0.961 |

## Code References
- https:/thecleverprogrammer.com/2020/11/24/flower-recognition-with-python/
- https:/www.tensorflow.org/hub/tutorials/image_feature_vector
- https:/www.codemyroad.com/post/flower-recognition-with-python
- https:/iq.opengenus.org/resnet50-architecture
- https:/iq.opengenus.org/vgg19-architecture
