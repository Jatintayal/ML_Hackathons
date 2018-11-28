### Kaggle-Toxic Comment Classification
This is a Project in an IPython Notebook for the Kaggle competition, Toxic Comment Classification. The goal of this repository is to show how you can build a Recurrent Neural Network using keras and use it in multiclass classification like toxic comment classification.


#### Dependencies:
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [Keras] (https://keras.io/)


### Kaggle Competition | Toxic Comment Classification

Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.

The Conversation AI team, a research initiative founded by Jigsaw and Google (both a part of Alphabet) are working on tools to help improve online conversation. One area of focus is the study of negative online behaviors, like toxic comments (i.e. comments that are rude, disrespectful or otherwise likely to make someone leave a discussion). So far they’ve built a range of publicly available models served through the Perspective API, including toxicity. But the current models still make errors, and they don’t allow users to select which types of toxicity they’re interested in finding (e.g. some platforms may be fine with profanity, but not with other types of toxic content).

In this competition, you’re challenged to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and respectful.

Disclaimer: the dataset for this competition contains text that may be considered profane, vulgar, or offensive.

From the competition [homepage](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).

### Goal for this Notebook:

*	The goal is to show how you can build deep recurrent neural network with LSTM using keras for text classification purposes.

#### This Notebook will show examples of:

*	Data handling
*   Importing Data with Pandas
*   Cleaning Data
*	Split the training data into train, dev sets.
*	Convert words into vectors.
*	How to use word embeddings.
*   How to make a Recurrent Neural Network using keras.
*	How to use LSTM, Dropout in a RNN architecture.
*	How to use your model on a completely new dataset to see how well this model does.


Competition Website: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge
