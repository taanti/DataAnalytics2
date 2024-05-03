# Learn Data Analytics Part 2

In htis week, we will continue our journey to learn about data analytics. We will learn about the data analytics process, data storytelling, data mining concepts, and machine learning regression. We will also explore various data visualisation techniques and tools to help you create compelling data visualisations that communicate insights effectively. By the end of this week, you will have a solid understanding of data visualisation techniques and how to create various types of plots using Python libraries such as Matplotlib and Seaborn. Let's get started!

## Importing Libraries

- Importing libraries is a crucial step in data analysis as it allows you to access a wide range of functions and tools that can help you perform various tasks. In Python, you can import libraries using the `import` keyword followed by the library name.

```# Importing the NumPy and Pandas library with the alias 'np' with the alias 'pd'
import numpy as np
import pandas as pd
# Importing the pyplot module from the Matplotlib library with the alias 'plt'
import matplotlib.pyplot as plt
# Jupyter Notebook magic command to display Matplotlib plots inline
%matplotlib inline
# Importing the Seaborn library with the alias 'sns'
import seaborn as sns
```

## Data Analytics Process

Data Analytics Process is a systematic approach to analyzing data and extracting insights from it. Progressing through the stages of the Data Analytics Process allows you to gain a deeper understanding of your data and make more informed decisions based on the insights you uncover. The Data Analytics Process typically involves the following stages:

1. **Descriptive Analytics**: Descriptive Analytics involves summarizing and interpreting historical data to gain insights into past events and trends. It helps you understand what has happened in the past and identify patterns and relationships in your data.

2. **Diagnostic Analytics**: Diagnostic Analytics involves identifying the root causes of events and understanding why certain things happened. It helps you uncover the factors that contributed to specific outcomes and provides insights into the relationships between variables.

3. **Predictive Analytics**: Predictive Analytics involves using historical data to forecast future events and trends. It helps you predict what is likely to happen in the future based on past data and trends.

4. **Prescriptive Analytics**: Prescriptive Analytics involves recommending actions to optimize outcomes and achieve specific goals. It helps you make informed decisions by providing recommendations on the best course of action to achieve desired outcomes.

## Data Story Telling

Data Storytelling is the process of using data visualisation techniques to communicate insights and findings from data analysis effectively. By creating compelling data visualisations, you can tell a story with your data, making it easier for your audience to understand and interpret the information you are presenting.

Dataset: Supermarket Purchase History

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Dataset%20Supermarket.png" /></div>

Example of Data Story Telling:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Data%20Story%20Telling.png" /></div>

From the description of supermarket data above, data is obtained that there is a purchase history in a supermarket where the average number of items purchased by buyers is 5 and the amount of purchases made is 55 Dollar. Then, the most purchases reached almost 100 Dollar and with a maximum number of purchases of 10 units

## Data Mining Concepts

Data Mining Concepts are techniques used to extract useful information from large datasets. By applying data mining concepts, you can uncover patterns, relationships, and insights in your data that can help you make more informed decisions and gain a deeper understanding of your data.

### Correlation

Correlation is a statistical measure that describes the relationship between two variables. It indicates how one variable changes in relation to another variable. Correlation values range from -1 to 1, with -1 indicating a perfect negative correlation, 0 indicating no correlation, and 1 indicating a perfect positive correlation. There was a 2 types of correlation the first is Positive Correlation and the second is Negative Correlation.

Example of Correlation:

- Positive Correlation: More vehicles leave the city as Eid al-Fitr approaches.
- Negative Correlation: Temperature drops as altitude increases.

### Data Correlation

Data Correlation is a technique used to identify relationships between variables in a dataset. It helps you understand how variables are related and how they influence each other. By analyzing data correlation, you can uncover patterns and relationships in your data that can help you make more informed decisions.

Example of Data Correlation:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Data%20Correlation.png" /></div>

The example above shows the correlation matrix of a dataset. The correlation matrix displays the correlation coefficients between variables in the dataset. The correlation coefficients range from -1 to 1, with -1 indicating a perfect negative correlation, 0 indicating no correlation, and 1 indicating a perfect positive correlation.

### Anomaly and Outlier

Anomaly and Outlier is an important concept in data analysis as they can provide valuable insights into the data and help you identify potential issues or opportunities in your data. By detecting anomalies and outliers, you can gain a deeper understanding of your data and make more informed decisions based on the insights you uncover. Anomaly and Outlier are often used interchangeably, but they have different meanings:

1. Anomaly is an observation that deviates significantly from other observations in a dataset. It is an unusual or unexpected data point that does not conform to the normal pattern of the data. Anomalies can be caused by errors in data collection, measurement errors, or unusual events that occur in the data.

2. Outlier an observation that lies outside the overall pattern of a dataset. It is a data point that is significantly different from other data points in the dataset. Outliers can be caused by errors in data collection, measurement errors, or unusual events that occur in the data.

- Outlier Processing :
  Identifying and addressing values in data to ensure analysis accuracy. Steps include outlier identification, setting bounds, and actions like removing or transforming outlier values. Validation is essential for analysis integrity.

Example of Outlier Processing:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Outlier%20Processing.png" /></div>

### T-Test and P-Value

T-Test and P-Value are statistical tests used to determine if there is a significant difference between two groups. T-Test compares the means of two groups and determines if the difference between them is statistically significant. P-Value is a measure of the strength of the evidence against the null hypothesis. A low P-Value indicates that the difference between the groups is statistically significant. There are two types of T-Tests:

- H0: There is **no significant** difference between the two groups.
- H1: There is **a significant** difference between the two groups.

Example of T-Test and P-Value:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/T-Test.png" /></div>

Example above shows the T-Test and P-Value results for two groups of data. The T-Test results indicate that there is a non-significant difference between the two groups, while the P-Value results indicate that the difference between the two groups is not statistically significant.

### Regression

Regression is a statistical technique used to model the relationship between two or more variables. It helps you understand how one variable changes in relation to another variable and predict the value of one variable based on the value of another variable. Here we have study about the Linear Regression.

Data :

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Data.png" /></div>

- Exploratory Data Analysis (EDA) is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. A statistical model can be used or not, but primarily EDA is for seeing what the data can tell us beyond the formal modeling or hypothesis testing task.

Example of Exploratory Data Analysis (EDA):

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/EDA%201.png" /></div>

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/EDA%202.png" /></div>

The example above shows the exploratory data analysis of a dataset. The exploratory data analysis involves visualizing the data to identify patterns, trends, and relationships in the data. The exploratory data analysis helps you gain a deeper understanding of the data and uncover insights that can inform further analysis.

- Preprocessing Modelling :

Preprocessing Modelling is a technique used to prepare data for analysis and modeling. It involves cleaning, transforming, and organizing data to make it suitable for analysis. Preprocessing Modelling helps you ensure that the data is accurate, complete, and consistent, which is essential for building accurate and reliable models.

Data we used was cleaned and transformed to make it suitable for analysis. The data was organized into a format that could be used to build a regression model. The preprocessing modeling step helps ensure that the data is accurate, complete, and consistent, which is essential for building an accurate and reliable regression model. Splitting the data into training and testing sets is an important step in building a regression model. The training set is used to train the model, while the testing set is used to evaluate the model's performance.

Example of Preprocessing Modelling:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Pre%20Processing.png" /></div>

- Machine Learning Regression - Simple Linear Regression :

Simple Linear Regression is a statistical technique used to model the relationship between two variables. It helps you understand how one variable changes in relation to another variable and predict the value of one variable based on the value of another variable. Simple Linear Regression involves fitting a linear model to the data and using the model to make predictions.

Example of Machine Learning Regression - Simple Linear Regression:

Fit the Regression Model:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Fitting%20Into%20Training.png" /></div>

Predictions using the Regression Model:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Result.png" /></div>

- Visualization of Regression Model:

Visualizing the regression model helps you understand the relationship between the independent and dependent variables and assess the accuracy and reliability of the model. There are several types of plots used to visualize regression models, including bar diagrams and scatter plots.

Bar Diagram:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Bar%20Plot.png" /></div>

Scatter Plot:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Scatter%20Plot.png" /></div>

The example above shows the results of a simple linear regression model. The regression model fits a linear line to the data and uses the line to make predictions. The bar diagram and scatter plot visualize the relationship between the independent and dependent variables and show how well the regression model fits the data.

- Evaluation of Regression Model:

Evaluation of the regression model is an important step in assessing the accuracy and reliability of the model. There are several metrics used to evaluate the performance of a regression model, including:

- **Mean Squared Error (MSE)**: Measures the average squared difference between the actual and predicted values.
- **Mean Absolute Error (MAE)**: Measures the average absolute difference between the actual and predicted values.
- **R-Squared (R2)**: Measures the proportion of the variance in the dependent variable that is predictable from the independent variable.

Example of Evaluation of Regression Model:

<div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/DataAnalytics2/Evaluate%20Model.png" /></div>

## End Notes

We have covered the data analytics process, data storytelling, data mining concepts, and machine learning regression in this week's lesson. We have also explored various data visualisation techniques and tools to help you create compelling data visualisations that communicate insights effectively. By the end of this week, you should have a solid understanding of data visualisation techniques and how to create various types of plots using Python libraries such as Matplotlib and Seaborn. I hope you found this lesson informative and engaging. See you next week!
