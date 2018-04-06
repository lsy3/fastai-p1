# fastai-p1
Practical Deep Learning For Coders, Part 1 [fast-ai site](http://course.fast.ai/)

## HW Description
1. HW01: Image classification with CNN (Glass vs Plastic)
    - Data was downloaded using google image search + chrome downloader extension. To help chrome download plugins to download image easier, don't forget to do "Advance Search" and set the "usage rights" to "free to use or share".
    - Results: 96.7% (1 mistake)
1. HW02: Image multi-label classification [kaggle plant-seedlings-classification](https://www.kaggle.com/c/plant-seedlings-classification)
    - Data was downloaded using Kaggle CLI and added to './data/<comp_name>'
    - Best Results: 0.98236 (kaggle)
1. HW03: Melbourne Housing Price Prediction [data source](https://www.kaggle.com/anthonypino/melbourne-housing-market/data)
    - Data was downloaded using Kaggle CLI and added to './data/melbourne-housing'
    - Best R2 result: ~80%
1. HW04a: Pytorch Tutorial [link](http://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)
1. HW04b: Basic Sentiment Analysis using Pytorch Text
    - Data was downloaded from [link](https://archive.ics.uci.edu/ml/machine-learning-databases/00331/sentiment%20labelled%20sentences.zip) and added to './data/sentiment'
    - Best Result for IMDB: 0.9889
1. HW05: (Stochastic) Gradient Descent and ADAM Optimizer implementation
    - SGD was based from fastai notebook
    - ADAM was based from [arxiv paper](https://arxiv.org/abs/1412.6980)
1. HW06a: Char level RNN based from [link](http://pytorch.org/tutorials/intermediate/char_rnn_generation_tutorial.html)
    - Tried producing text learned from the Psalms (Bible, KJV).
    - The result was not that well. The output keeps on cycling through the same words.
1. HW06b: Char level LSTM based from the fast-ai RNN notebook (lesson 6)
    - Tried producing text learned from the Psalms (Bible, KJV).
    - The results were a lot better, but there is still areas for improvement.

## Setting Up Work Environment
1. Google instance with GPU [link](https://medium.com/@howkhang/ultimate-guide-to-setting-up-a-google-cloud-machine-for-fast-ai-version-2-f374208be43)
1. Download kaggle data using Kaggle CLI [link](https://github.com/Kaggle/kaggle-api)
1. Extract .7z with "7z e <filename>", .tar with "tar -xvf <filename>", .zip with "unzip <filename>

