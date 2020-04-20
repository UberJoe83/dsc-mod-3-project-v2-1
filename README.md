
# Module 3 Final Project


## Introduction

For this project we were tasked with choosing a dataset and building a classification model using what we have learned about Data Science and Machine Learning. My favorite sport is Baseball so I decided to go with data containing statistics about the different pitchers in the MLB(Major League Baseball). Over the years the game has changed, teams nowadays are using stats and data analysis to make decisions about building a team to win the coveted WORLD SERIES! With that in mind, the focus here will be on predicting the performance of the pitchers in order to aid the Front Office make decisions about who to acquire for the following season. 


## Approach

**OSEMN** framework:
1. Obtain
2. Scrub
3. Explore
4. Model
5. Interpret

## Sean Lahman's Baseball Dataset

The data used in this project was obtained from http://www.seanlahman.com/baseball-archive/statistics/.
There you can find the different tables available with various baseball stats dating all the way back to 1871,
complete with documentation and descriptions of the content of the different tables of data. I chose to download
the CSV version of the data so that I could manipulate it with the Pandas library. 

## The Models

The main goal of this project was to create a classification model. I used the following classifiers in my project:

1. Logistic Regression
2. Random Forest
3. XGBoost

Logistic Regression and XGBoost were the best performing models, both with ~90% accuracy, but the Logistic Regression Model had less overfitting than XGBoost.


## Repository Content

* **student.ipynb** is the Jupyter Notebook used to complete this project.
* **columns.rtf** contains the list of features used and their descriptions.
* **MOD 3 V2 final project.pptx** is the "Executive Summary" presentation.
* **model_data_1.csv** contains the scrubbed data to use for modeling.
* **People.csv** contains personal information about the players.
* **Pitching.csv** is the raw pitching statistic dataset, the data used in modeling was extracted from here.
* **single_stint_df.csv** contains the data set after it's first round of scrubbing.


