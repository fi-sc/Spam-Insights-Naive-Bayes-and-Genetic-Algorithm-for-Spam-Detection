# Spam Insight: Naïve Bayes and Genetic Algorithm for Spam Detection

## Description
The development of spam filtering systems have been demonstrated through various methodologies, with Multinomial Naïve Bayes establishing itself as one of the most accepted and popular approach. Metaheuristic algorithms such as evolutionary algorithms have proven effective in addressing real-world problems with Genetic Algorithms standing out as a versatile optimisation technique. However, GA remains underused within the context of spam filtering. The proposed system, a combination of MNB and GA, introduces a novel and potentially effective approach.

## Features
- Multinomial Naive Bayes
- Genetic Algorithm
- TF-iDF
- Dashboard

## Software
This code requires Python 3 to run. Python 3 can be downloaded from: https://www.python.org/downloads/

## How to use

1. In terminal: pip install -r requirements.txt
    - this installs all the packages and libraries needed to run the system
    
2. Then choose either method:

A - Running both notebooks:
- Download the 9 folders in **Enron-Spam in raw form** dataset from: https://www2.aueb.gr/users/ion/data/enron-spam/ uzip and save to a folder called 'RawData'
- Run **'LoadData.ipynb'** to save the dataset as a CSV file
    - this step uses the Raw Data previously downloaded to create 2 new folders called 'Spam' and 'Ham' which are used to create the CSV file
- Run **'ModelMetrics.ipynb'** to create the model and dashboard
    - this step uses the CSV file created

B - Running one notebook:
- Run **'ModelMetrics.ipynb'** to create the model and dashboard
    - **'LoadData.ipynb'** doesn't need to be run, as this step uses the CSV file within the repository to create the system


3. At the bottom of **'ModelMetrics.ipynb'**, there will be a link to the dashboard created when the whole notebook runs   
