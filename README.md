# Aspect Based Sentiment Classification

As part of our CS 583 Data Mining and Text Mining course final project, we were tasked to perform **Aspect Based *Sentiment Analysis***

---
### Problem Statement

We were given training data in the form of 2 **comma separated values** files and were given the liberty to perform classification with the help of any classifier of our choice.

I decided to use **Naïve-Bayes** and **Support Vector Machines** to perform classification.

There is a catch though. In-order to take the **aspect** into account, I used dependency tree parsing to generate certain rules that enabled us to classify the sentiment according to just the aspect and not the whole sentence.

---
### Tools

To perform the *Natural Language Processing* task involved, I used **Spacy** the industrial grade NLP parser. It can be found [here](https://spacy.io/).

I used Python's rich Machine Learning library, **Scikit Learn** to perform all the required Machine Learning tasks.

---

This repository includes 2 Jupyter Notebooks which has the source code and also I have saved our ML models as pickles (.pkl)

To execute the code, just run the Jupyer Notebooks and you can see the output.
