# Red Wine Quality Prediction using Linear Regression

This project aims to predict the quality of red wine using linear regression. Each wine in the dataset is given a "quality" score between 0 and 10. For the purpose of this project, the output is converted to a binary output where each wine is either classified as "good quality" (a score of 7 or higher) or not (a score below 7).

## Dataset

The dataset used for this project contains the following 11 input variables that determine the quality of a wine:

1. Fixed acidity
2. Volatile acidity
3. Citric acid
4. Residual sugar
5. Chlorides
6. Free sulfur dioxide
7. Total sulfur dioxide
8. Density
9. pH
10. Sulfates
11. Alcohol

## Methodology

The project utilizes linear regression to predict the quality of red wine. Linear regression is a statistical approach for modeling the relationship between a dependent variable (quality) and one or more independent variables (input variables). By fitting a linear equation to the observed data, the model can make predictions on new data.

To convert the quality score into a binary output, a threshold of 7 is used. Wines with a quality score of 7 or higher are classified as "good quality", while wines with a score below 7 are classified as not "good quality".

## Results

The results of the linear regression model can be evaluated using various metrics such as accuracy, precision, recall, and F1 score. These metrics provide insights into the performance of the model in predicting the quality of red wine.

## Conclusion

In conclusion, this project demonstrates the use of linear regression for predicting the quality of red wine. By converting the output to a binary classification, the model can effectively classify wines as "good quality" or not. The results obtained from the model can be used to make informed decisions in the wine industry.

## References

- Dataset: [Red Wine Quality](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009)
