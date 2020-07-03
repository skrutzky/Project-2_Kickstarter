This project considers that we are a non-profit organization that helps people to find out **which probability they have to get funded** by kickstarters with their projects and what they **can do to improve their chances**.   

## The Repository consists of:
* Project 2 Kickstarter - Dataset.pdf summarizing findings in presentation-style
* DS-Project-2_Kickstarter.ipynb Jupyter Notebook containing the code and steps of analyzing data
* a figure showing the 5 most important influencers for the AdaBoost Model

## Summary
* AdaBoost model performs best with an accuracy of 80%
* Random Forrest has a very high recall for successful cases but the recall for failure prediction is very low => is not what we are looking for, we want to have a high accuracy to identify both success and failure
* with the AdaBoost model 70% of failure and 86% of successful cases can be predicted correctly
* most important influencers in AdaBoost are
    * the goal set
    * how many projects a creator has running
    * the time phase until an project expires (project duration)
    * the usd type international
    * and the length of the blurb
* Random Forrest has at least goal, count_creator_id and duration as most important features
* goal is also in logistic regression one of the most important features
* projects in Hongkong have the highest chance to be successful, projects from Italy have only less than 50% chance

## Outlook
* further data cleaning, e.g. remove outliers from the data
* get out most important features from SVM to identify the most common feature that influence success
* check if further new variables can help to improve the models
* check other models
* Take a look on these projects which have collected more money as they initial wanted 
* analyze how backers count might be affected to find out what attracts many backers