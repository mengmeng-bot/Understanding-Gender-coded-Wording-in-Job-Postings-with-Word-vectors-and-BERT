# Understanding-Gender-coded-Wording-in-Job-Postings-with-Word-vectors-and-BERT
Understand Gender-coded Wording in Job Postings

This is my class project for CS224N, winter 2021

Requirements:

    pip install tensorflow-gpu==1.5.0

    pip install bert-tensorflow==1.0.1

    pip install genderdecoder

Download the dataset from Kaggle (requires login)

Running the project

Use word vectors to find additional gender-coded words

    preprocess the dataset and train GloVe vectors to identify new gender-biasd words using [224N project_word vector.ipynb]

BERT

    prepare datasets for BERT using [224N project_dataset for BERT.ipynb]

    train BERT on training set and evaluate classification performance on dev set using [224N project_model.ipynb]

    test BERT performance on test set and compute gradients on each word using [224N project_model_test.ipynb]


