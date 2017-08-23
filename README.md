# Linear-Regression-in-R

Linear Regression is a very simple approach for supervised learning. It is a useful tool for predicting a quantitative response and most widely statistical learning method. linear regression is important because many fancy statistical learning approaches can be seen as generalizations or extensions of linear regression.
In this blog I will work on Boston dataset which is a default dataset in R package 'MASS'. Dataset includes 13 explanatory variables and a response variable and contains 506 rows and 14 columns.

Here are a few important questions that we might seek to address:

1.	Is there a relationship between explanatory variables and a response variable?
Our first goal should be to determine whether the data provide evidence of an association between explanatory variable and response variable. If the evidence is week then one might argue that this variable is statistically insignificant.

2.	How strong is the relationship between explanatory variables and the response variable?
Assuming that there is a relationship between explanatory variables and a response variable. We would like to show the strength of this relationship. In other words, given a certain values of explanatory variables, can we predict the response (medv) with a high level of accuracy.

3.	Which explanatory variable contribute to Response variable (medv)?
Do all the explanatory variables contributes to the response variable (medv), or do just one or two of the media contribute? To answer this question, we must find a way to separate out the individual effects of each explanatory variable.

4.	How accurately can we estimate the effect of each explanatory variable on Response variable?
For every explanatory variable, what is the individual effect of these variable on response variable and how accurately can we predict the effect of increase?

5.	How accurately can we predict future Response (medv)?
For any given values of predictors, we can predict future values for Response variable (medv). 

6.	Is the relationship linear?
If there is approximately a straight-line relationship between explanatory variable and a response variable, then linear regression is an appropriate tool. If not, then it may still be possible to transform the predictors or the response so that linear regression can be used. 
