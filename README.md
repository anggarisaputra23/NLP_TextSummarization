# NLP_TextSummarization

## Data used
The data used in this project is extracted from Liputan6.com. The data was also used  in the Koto et al. (2020) research. Liputan6.com is an online Indonesian news portal which has been running since August 2000, and provides news across a wide range of topics including politics, business, sport, technology, health, and entertainment. According to the Alexa ranking of websites at the time of writing, Liputan6.com is ranked 9th in Indonesia and 112th globally.

## Problem
How to accurately provide users with a concise and informative overview of a news or any larger body of text, while preserving the key ideas and essential information.

## Solution
leveraged pre-trained language models to generate text summarization over the dataset with  diverse transformer-base models.

## Data Understanding & Data Preparation
The dataset consist of article and summarization corpus with over 200k documents. The dataset is harvested over a 10-year window — from October 2000 to October 2010 — to create a large scale summarization corpus, comprising 215,827 document–summary pairs.

Each data consist of :
1. data id
2. url of the news
3. news content
4. abstractive summary
5. extractive summary

There are no missing values and duplicates values in the dataset. The project use sample from the dataset to finetune pre-trained model.
Sample used are as follows:
1. Train : 2000 sample from 193.883 total rows
2. Test  : 1000 sample from 10.972 total rows
3. Validation : 1000 sample from 10.972 total rows

## Conclusion
![image](https://github.com/user-attachments/assets/ef673a71-9ca5-4da8-9148-4e80810143ed)

