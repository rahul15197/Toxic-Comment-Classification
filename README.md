# Toxic-Comment-Classification
## Toxic Comment Classification using GPU Accelerated LSTM

Toxic Comment Classification is a project built with python that uses Machine Learning to classify a comment into several categories.

Those Categories are "toxic", "severe_toxic", "obscene", "threat", "insult", "identity_hate".

Dataset is available [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data).

For the purpose of classification a Neural Network Model is used that is CuDNNLSTM (gpu accelerated LSTM). If you want to run it on only cpu or facing difficulties with installation of CUDA for CuDNNLSTM, just replace the CuDNNLSTM with LSTM in the code.

Working of CuDNNLSTM is same as LSTM, it just speeds up the training and testing by using gpu as well. 

For any help regarding the project, drop a mail @ [Rahul Maheshwari](mailto:rahul.maheshmaheshwari@gmail.com?subject=[GitHub]%20Source%20Han%20Sans)

## Installation

For running the project you need to import following libraries

```bash
nltk (data preprocessing)
keras (recommended version = 2.2.5)
tensorflow (recommended version = 1.14)
pandas (dataframe)
re (regular expression used in preprocessing)
matplotlib (to plot graphs)
sklearn (dataset train test split)
string (string operation)

```

## Usage

Run the program using 
```bash
python toxic_comment_classification.py
```

## Contribution
Project created by [Rahul Maheshwari](https://www.linkedin.com/in/rahul-maheshwari-597bb2b6/)

