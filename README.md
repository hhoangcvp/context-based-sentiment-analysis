# SemEval-2013: Sentiment Analysis in Twitter
Sentence-Level Sentiment Analysis

## Descriptions
**One model to learn them all** (both language model and sentiment analysis -> sentiment2vec)
![alt text](https://raw.githubusercontent.com/peace195/Semeval2013/master/model.png)

## Version
* se-v1.ipynb: using sum all LSTM output vectors to predict sentiment label.
* se-v2.ipynb: using sum all LSTM output vectors of **[sentiment word](https://github.com/peace195/sentiment-analysis-in-twitter/tree/master/dict)** to predict sentiment label.
* se-v3.ipynb: using [sentiment embedding](http://aclweb.org/anthology/P14-1146) instead of one-hot vector.

## Data & Result
* [https://www.cs.york.ac.uk/semeval-2013/task2.html](https://www.cs.york.ac.uk/semeval-2013/task2.html)
* 67% accuracy rate

## Prerequisites
* tensorflow 1.2
* ipython notebook

## Author
**Binh Do**
