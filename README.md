# Multi-label Comment Toxicity Detection using Deep Learning

I was learning about Neural Networks and Natural Language Processing so I created this project using tensorflow to consolidate my learning. This project employs deep learning techniques to categorize online comments based on their level of toxicity. Six categories of toxicity are recognized: "Toxic", "Severe Toxic", "Obscene", "Threat", "Insult", and "Identity Hate". This model might help you finally win arguements on Reddit!

# Overview

- Data Preprocessing: The raw comment text data undergoes a series of transformations to ensure it's loaded into tensorflow. This includes conversion to lower-case, removal of punctuation and stop words, and TextVectorization.
-  Model Construction:  A sequential model is constructed using TensorFlow's Keras API. The model is composed of the following layers:

-- An embedding layer for capturing semantic relationships between words.
-- A bidirectional LSTM layer for understanding the context in both directions of the sentence.
-- Multiple dense layers for feature extraction and abstraction.
-- The final dense layer with sigmoid activation function for multilabel classification.

- Model Training
- Performance Evaluation using Recall, Precision and Accuracy
- Deployment using Gradio


# Usage

1. git clone https://github.com/tanveersingh10/toxicity-deep-learning

2. pip install -r requirements

3. jupyter notebook toxicity-deep-learning.ipynb
