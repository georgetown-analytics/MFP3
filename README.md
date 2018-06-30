# FP3
Project Title: Financial Performance Prediction Project (FP3)
Cohort 11 Capstone Project for the Certificate of Data Science at Georgetown University School of Continuing Studies.

Expected Release Date: 30 June 2018

Purpose: To predict whether stock prices will rise or fall within the first three months after an IPO

Team Members: MD Alam, Riley Back, Melissa Burn, Michael Iapalucci, Murali Kannan

Methodology: Assess the sentiment of news headlines about the subject IPO for the period leading up to and after the IPO release. Then, using a classification-focused machine learning algorithm trained on ~5400 headlines covering 16 IPOs between 2010 and 2017, train a prediction model on the target of whether the stock will rise or fall in the first 3 months. After training, the model was tested on 2 newer IPOs, released subsequent to the first data capture.

Required Input: 

> FOR THE IPO: IPO Company, ticker symbol, industry, release date, manager, offer price

> FOR EACH HEADLINE: Headline text, source publication, date, day of the week, source tier, IPO Company

Predictive Output: "Up" or "Down" indicator of stock performance over first 90 days

Intended Users: The curious and casual.

Team Assessment: The team successfully predicted the stock price trajectory for two new IPOs. However, the data product relies on both CountVectorization and Primary Component Analysis to create a set of features that generate reliable predictions. However, the Team recognizes that there is no way to introduce new IPO data for a prediction and have the CountVectorization and PCA process generate the same set of features as was used in the training data. This is the next big challenge to be tackled for the data product.
