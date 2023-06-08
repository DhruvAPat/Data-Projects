# Smartwatch Fitness Data Analysis using Python

This repository contains Python code for analyzing the fitness data collected by smartwatches. With the increasing popularity of smartwatches, more and more people are using them to track their fitness. By analyzing the data collected by smartwatches, we can gain insights into our fitness levels and take steps to improve our health.

## Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Plotly Express
* Plotly Graph Objects

## Installation

To install the required libraries, run the following command:

```
pip install pandas numpy matplotlib plotly
```

## Usage

To use this code, simply clone the repository to your local machine and run the Jupyter notebook. The notebook contains Python code for analyzing the fitness data collected by smartwatches. You can modify the code as per your requirements and analyze your own fitness data.

## Data

The data used in this analysis is a sample dataset collected from a smartwatch. The dataset contains information about the user's heart rate, steps taken, calories burned, and distance traveled over a period of time.

## Analysis

The analysis performed in this notebook includes:

* Data cleaning and preprocessing
* Data visualization using Matplotlib and Plotly Express
* Correlation analysis
* Prediction using regression models

## Conclusion

By analyzing the data collected by smartwatches, we can gain insights into our fitness levels and take steps to improve our health. This notebook provides a basic framework for analyzing smartwatch fitness data using Python. You can modify the code as per your requirements and perform more advanced analysis to gain deeper insights into your fitness levels.

## Insights from the code

*print(data.isnull().sum())

![Screenshot (358)](https://github.com/DhruvAPat/SmartWatchAnalysis/assets/49668870/5600b21b-e446-4bfa-b9fe-66546f86f7f2)

So the dataset does not have any null values

*figure = px.scatter(data_frame = data, x="Calories",
                    y="TotalSteps", size="VeryActiveMinutes", 
                    trendline="ols", 
                    title="Relationship between Calories & Total Steps")
figure.show()

![Screenshot (360)](https://github.com/DhruvAPat/SmartWatchAnalysis/assets/49668870/45b19387-adfa-4aa5-9560-d2c4643383c5)
You can see that there is a linear relationship between the total number of steps and the number of calories burned in a day

##Summary
So this is how you can analyze the data collected by a smartwatch about fitness using Python. Smartwatches are preferred by people who like to take care of their fitness. Analyzing the data collected on your fitness is one of the use cases of Data Science in healthcare. 

