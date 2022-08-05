# BBC news classification analysis using natural language processing
> Deep learning prediction of BBC news articles using natural language processing

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
- In this natural language processing project, I will a BBC news dataset from Kaggle [BBC News Classification](https://www.kaggle.com/c/learn-ai-bbc/overview), which contains 2225 examples of news articles with their respective labels. 
- I am developing a model to perform classification of the BBC news articles into five categories: {1: 'sport', 2: 'business', 3: 'politics', 4: 'tech', 5: 'entertainment'}
- In this project, I am utilizing a combination of the Embedding layer, GlobalAveragePooling1D and two dense layers to perform the classification
- The project also contains pre-processing of the text corpus: tokenization, Sequences-truncating and -padding
- The model achieves an accuracy of 95% on the validation set after 30 epochs.
- Here is a snapshot of the training and validation loss during the training process.

![Example screenshot](loss.png)
![Example screenshot](accuracy.png)
<!-- If you have screenshots you'd like to share, include them here. -->

## Technologies Used
- Python
- Tensorflow
- Pandas
- Matplotlib
- Keras

## Room for improvement:
- Improvement could be made by doing transfer learning or using GloVe as a pre-trained embedding layer.

## Contact
Created by [Miralireza Nabavi](anabavib@asu.edu) - feel free to contact me!
