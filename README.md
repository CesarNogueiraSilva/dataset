# Tutorial on 3D Image Classification 

[![Hugging Face Spaces](https://img.shields.io/badge/🤗%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/keras-io/3D_CNN_Pneumonia)

Learn how to train a 3D convolutional neural network (3D CNN) to predict presence of pneumonia. Now on the Keras docs ([Link](https://keras.io/examples/vision/3D_image_classification/))!

## Dataset

The dataset used in this tutorial is by [MosMedData: Chest CT Scans with COVID-19 Related Findings](https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1) which consists of 200 3D CT scans in total for the two classes. More detail [here](https://github.com/hasibzunair/3D-image-classification-tutorial/releases/tag/v0.2). Note that the data is public and I've kept it here for easy access/usage.

## What is it about?

This tutorial will show the steps needed to build a 3D convolutional neural network (3D CNN) to predict the presence of viral pneumonia in computer tomography (CT) scans. 2D CNNs are commonly used to process RGB images (3 channels). A 3D CNN is simply the 3D equivalent: it takes as input a 3D volume or a sequence of 2D frames (e.g. slices in a CT scan), 3D CNNs are a powerful model for learning representations for volumetric data.

## Usage

You can run the entire notebook on Colab! Copy the [URL](https://github.com/hasibzunair/3D-image-classification-tutorial/blob/master/3D_image_classification.ipynb) of the notebook [here](https://colab.research.google.com/github/). 

## Acknowlegements
🤗 Spaces built by [Faizan Shaikh](https://github.com/faizankshaikh).

## References
Uniformizing Techniques to Process CT scans with 3D CNNs for Tuberculosis Severity Estimation ([Paper](https://arxiv.org/abs/2007.13224), [Code](https://github.com/hasibzunair/uniformizing-3D)).
