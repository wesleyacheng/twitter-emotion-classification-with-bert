# twitter-emotion-classification-with-bert

Posted on **[Kaggle](https://www.kaggle.com/code/wesleyacheng/twitter-emotion-classification-with-bert)** and hosted on **[HuggingFace](https://huggingface.co/wesleyacheng/twitter-emotion-classification-with-bert)**.

# Introduction

While I was making my **[Angry Birds Classifier](https://www.kaggle.com/code/wesleyacheng/angry-birds-classifier)** to classify if tweets are angry or not, I thought why don't we add **2** more emotions - **Joy and Sadness** into the mix!

<img width="369" alt="twitter-emotion" src="https://github.com/wesleyacheng/twitter-emotion-classification-with-bert/assets/15952538/cdab921c-915a-490d-8b74-aace461cddaf">


Here we will be creating a **Multiclass Text Classifier** that classifies tweets as either having **JOY, SADNESS, or ANGER**.

We will use the [Twitter Emotion Dataset](https://huggingface.co/datasets/tweet_eval/viewer/emotion/train) and [BERT](https://huggingface.co/distilbert-base-uncased) to do [Transfer Learning](https://en.wikipedia.org/wiki/Transfer_learning) with [PyTorch](https://pytorch.org) and [HuggingFace](https://huggingface.co).
