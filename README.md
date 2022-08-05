# Image segmentation of the Pet dataset using Unet

## Table of Contents
* [General Info](#general-information)
* [Results](Results)
* [Technologies Used](#technologies-used)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
- The goal of the project is to develop a model to perform semantic image segmentation on the pet images
- I am using a Unet neural network architecture which consists of an encoder and decoder section. This architecture is also a fully convolutional network:

![Unet](Unet.png)
![Encoder](Encoder.png)
![Decoder](Decoder.png)

- The dataset is Oxford Pets - IIT dataset [BBC News Classification](https://www.robots.ox.ac.uk/~vgg/data/pets/). This dataset contains pet images, their classes, segmentation masks and head region-of-interest. I will only use the images and segmentation masks in this project. This dataset is already included in TensorFlow Datasets and we can simply download it. The segmentation masks are included in versions 3 and above.
- The model achieves an accuracy of 85% on the validation set after 15 epochs.
- I ran the notebook on Arizona State University's supercomputing cluster using two Tesla V100 GPUs. The information regarding the GPUs is included at the end of the notebook.

## Results

![Example screenshot](Result1.png)
![Example screenshot](Result2.png)
<!-- If you have screenshots you'd like to share, include them here. -->

## Technologies Used
- Python
- Tensorflow
- Pandas
- Matplotlib
- Keras

## Contact
Created by [Miralireza Nabavi](anabavib@asu.edu) - feel free to contact me!
