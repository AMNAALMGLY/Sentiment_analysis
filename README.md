# Sentiment_analysis
In this notebook i go through the steps of implementing FastText Model for text classification , using IMBD dataset . this is the [paper](https://arxiv.org/pdf/1607.01759.pdf) that proposed this model .
# How it works 
it is simply a linear classification with biagram featrues as input to the embedding layer averaged across word axis , then the linear layer follows where the output will be either positive or negative.(after a sigmoid loss).
