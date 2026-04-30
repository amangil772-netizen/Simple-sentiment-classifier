# Simple-sentiment-classifier
*Student:* Aman Gill | UB: 23055704  
*Module:* COS6031-D Applied AI Professional — Portfolio Evidence  
*Level:* Simple Project  
*Date:* April 2026

---

## What this does

Classifies text into one of two categories using a basic machine 
learning pipeline. Built using the 20 Newsgroups dataset with 
TF-IDF vectorisation and Logistic Regression.

## How to run

Open the notebook in Google Colab and run all cells in order.

## Results

- Accuracy: 95.60%
- Precision: 92.87%
- Recall: 98.74%
- F1 Score: 0.9572

## What I used

- Python
- Scikit-learn
- TF-IDF Vectoriser
- Logistic Regression

## What I learnt

TF-IDF converts text into numbers the model can learn from.
Each document becomes a vector showing how important each word 
is relative to the whole dataset. I had studied this in lectures 
but implementing it properly made it click — especially seeing 
how vocabulary size affects both accuracy and training time.

This pipeline uses the same supervised learning workflow as the 
AVC&C project — features in, labels out, evaluate on test data. 
The difference is just the type of feature (text vs image frames).

## Files

- sentiment_classifier.ipynb — full notebook with all code and outputs
