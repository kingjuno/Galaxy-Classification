
# Pneumonia Detection
[![Heroku](https://heroku-badge.herokuapp.com/?app=galaxyclassification)](https://galaxyclassification.herokuapp.com/)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/kingjuno/Galaxy-Classification/blob/master/notebook/galaxy_zoo_checkpoint.ipynb?flush_cache=true)



### Detecting Pneumonia from chest X-Ray images using PyTorch.
The model architecture used is [resnet18](https://arxiv.org/pdf/1512.03385) which is trained using PyTorch, and then converted to ONNX format for deployment using Heroku.
Galaxy Zoo is a crowdsourcing project, where users are asked to describe the morphology of galaxies based on images. They are asked questions such as “How rounded is the galaxy” and “Does it have a central bulge”, and the users’ answers determine which question will be asked next. The questions form a decision tree which is shown in the figure below, 
![](assets/2022-02-11-12-21-40.png)

## Dataset 📂
Dataset used for training is from Kaggle [Galaxy zoo](https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge/data) which contains over 140,000 images of various galaxies.



## Notebook 📒
View the notebook here: [pneumonia-det.ipynb](https://nbviewer.org/github/kingjuno/Galaxy-Classification/blob/master/notebook/galaxy_zoo_checkpoint.ipynb)



## Deployment 🚀
The model has been been converted to ONNX format and deployed using Gradio & hosted on Heroku: [Galaxy Classification](https://galaxyclassification.herokuapp.com/)


## Predictions 🔍
Predictions on unseen test data:

![samplepred](assets/classification.gif)