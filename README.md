# Automatic ticket clssifcation 
> This project aims to classify customer complaints based on products or services to expedite issue resolution. Utilizing a JSON dataset of unlabelled customer complaints, the goal is to segregate these tickets into five predefined clusters: Credit card/Prepaid card, Bank account services, Theft/Dispute reporting, Mortgages/loans, and Others. The approach we took leverages topic modelling to create labelled data for training supervised models, ultimately enhancing the efficiency of complaint resolution in customer support.

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information
The project involves several key tasks:
`Data Loading`: Importing and understanding the structure of the JSON dataset containing customer complaints.
`Text Preprocessing`: Cleaning and preparing text data, including removing stop words, stemming, and tokenization to make it suitable for analysis.
`Exploratory Data Analysis (EDA)`: Visualizing and summarizing the data to understand the distribution and characteristics of the complaints.
`Feature Extraction`: Converting text data into numerical features using techniques like TF-IDF to facilitate machine learning.
`Topic Modelling`: Applying Non-Negative Matrix Factorization (NMF) to identify underlying patterns and group complaints into the predefined categories.
`Model Building `: Training models like Logistic Regression, Decision Tree, or Random Forest using the labelled data from the topic modelling phase. Assessing model    performance using metrics such as accuracy, precision, recall, and F1-score to ensure robust classification.
`Model Inference`: Applying the trained model to classify new customer complaints into the relevant departments.

## Conclusions
- Logistic Regression model gives us the best f1-score of 94%.
- Logistic Regression model sucessfully predicted the topics complaint sample. Therefore, our model efficiently classifies customer complaints. 

## Technologies Used
- pandas - version 2.1.2
- numpy - version 1.26.1
- matplotlib - version 3.7.1
- seaborn - version 0.13.0
- sklearn - version 1.5.0
- plotly - version 5.22.0
- tqdm - version 4.66.2
- nltk - version 3.8.1
- spacy - version 3.7.5
- en_core_web_sm - version 3.7.1
- json - version 2.0.9

## Acknowledgements
- Greatful to upgrad for giving a chance to work on this project.

## Contact
Created by [@tejaswini1968] - feel free to contact me!


