# Stroke Risk Prediction
A model that calculates the risk in which users pose for a stroke based on their demographic and biological data. This project aims to help users understand which factors may contribute to their stroke risk and provide insights beyond a simple “Yes” or “No” prediction.

## Description

There are many factors that affect the risk of a stroke, and each one plays a different role. By encoding the data and producing plots, I was able to observe the strength in which each factor weighed in. The weak factors were dropped from the dataset whereas, the stronger factors were kept and values providing the strength of the correlation are displayed in a Heatmap.

## Limitations

The model provides risk estimates and should not be taken as a medical diagnosis and you should always consult a healthcare professional for medical advice.

## How to use it 

Once you run the code with 'Run All', you will be prompted to input your data and the model will then output a prediction of your risk of a stroke.

## How I made it

Using a dataset with over 5,000 entries, I first cleaned the data by dropping any columns which weren't factors or had no correlation. Dropping duplicates and null values maintained the accuracy of the model, followed by converting all strings to integers so the values can fit the model.

Used Machine Learning techniques to find correlations between the user's data and the risk of a stroke. The following Supervised Learning models were used to predict the user's risk of a stroke: Logistic Regression, Decision Tree Classifier, and Random Forest Classifier. Each of these models achieved >91% accuracy.

## Installation

If you would wish to download and run the model yourself, there are a few simple steps you must follow: 
1. Clone the repository: 
- Navigate to the desired folder in your terminal ("cd ~/Documents/Example").
- Clone the repository, "git clone https://github.com/barissucu/stroke_prediction.git".
- Open new folder "stroke_prediction" in your preferred IDE.

2. Run the notebook: 
- In the first cell, there is a commented line of code: "pip3 install (...)", run this cell in your terminal. (If on windows use pip rather than pip3).
- Once all libraries are downloaded, run the rest of the notebook! 

All the Pre-Processing code, plots, model creation and testing are in that one notebook!
