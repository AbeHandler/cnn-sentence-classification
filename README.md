# Convolutional Neural Networks for Sentence Classification

This is an extension of yoonkim's implementation of CNN_sentence to classify test sentences.
The original implementation can be found here: https://github.com/yoonkim/CNN_sentence

The file conv_net_classes.py is the same file from original implementation.
The files conv_net_sentence.ipynb and process.ipynb are modified files.

The original rt-polarity.neg and rt-polarity.pos files consisted of 5331 examples each. I took 50 examples from each of them to create
the test.data file. Here rt-polarity.neg, rt-polarity.pos, test.data consists of 5281, 5281 and 100 examples.

First 50 examples of test.data are of negative sentiment, rest are of positive sentiment.  
