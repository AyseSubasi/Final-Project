# Fake news detection - Final Project 
by Ayse Subasi - Ironhack Berlin




![<test>](nlppipeline.png)



## Overview

In this project I'm using two datasets from Kaggle(Real/Fake Data) to get better insights into news. My Goal is to predict wheater a givien news is fake news or real.


You can find my presentation here: [FAKE NEWS PRESENTATION](https://docs.google.com/presentation/d/1EbNREB32czgayLnX-TpxRI9maS30daqWMb_eRhrSu34/edit#slide=id.gf5d37a23ac_0_168)

## Dataset


Dataset:

[Kaggle - fake and real news dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)


+ 2 CSV Files Fake/ Real News
+ between 2015 - 2018
+ Fake: 23481 rows x 4 columns
+ Real: 21417 rows x 4 columns
+ Columns: Title, Text, Subject, Date
+ Missing values: 0 
+ Duplicates: 209

## Problems and Goals

+ Definitin of the Problem 
+ Cleaning the data 
+ Visualising insights
+ Modeling
+ Choosing a machine learning model which predicts fake news
+ Conclusion
+ Storytelling

## Tools

+ Python (Libaries: nltk, gensim , re, lexical-diversity.. )
+ Google Slides


## NLP Classification Pipline 



## Modeling

I used(X) with my lemmatized text and the title, my target variable was the classification True or False (0/1).

After comparing all results the winner is the Linear support vector machine.

Results:
    
Precision: 99 %
Recall: 99 %
F1score: 99 %


## Conclusion

You can see there is a differnce in the words:

Most frequent words in the fake dataset:21std century wire; video screen, image screen,getty image
Most frequent words in the fake dataset: Retuers, Days( Monday, Tuesdays, Friday), north korea

    
Ratio of uniqe words in the real dataset 98 % and 76 % in the fake one


Lengths of the sentence/words are in both the same


With the S

## Nice to have 

+ Using Deep learning models : Bert, Long Short Term Memory Networks
+ compare the results with unsupervised learning
+ Deploy a web application 


## WIP ...


```python

```
