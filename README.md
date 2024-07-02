# ElileKaggleP2
This repository holds part 2 of an intern project for Elile AI - Elile AI Intern Kaggle Competition.

This part is broken into sections:
- Section 1: Understanding model optimization and training techniques
- Section 2: Implementing these techniques in the given reference project

## Section 1: Understanding model optimization and training techniques

### Weighted Linear Regression
- Linear regression = a statistical model that estimates the linear relationship between certain factors
  - one dependent variable and one+ independent variables
- Using the line of best fit (regression line) we can make predictions on data (given independent variables)
- The "weighted" term comes in when we add more weight to points that are closer to the regression line

### Boosting Regression Trees
- Leaves have numerical values in regression trees (similar to decision trees)
- Rather than using linear regression, can use this if we have various independent variables and want to more easily manage everything
- Boosting is an adaptive method for combining numerous simpler trees into a parents tree
- Essentially combining weak learners into a strong learner

### Neural Networks
- Form the base of deep learning
- Take in data, train themselves to recognize patterns within data, predict output for new set of similar data
- In this project, we are using neural networks to forecast solar conditions and power generation

## Section 2: Implementing model optimization and further training techniques in given reference project

### Goal: To reduce training error to provide an increase in accuracy in solar energy predictions

- Stanford students randomized their examples and split them into train/dev/test sets. A better strategy would be to use sequences of data to account for the short-term, and how one days's weather affects the immediate next day (to a certain extent).
- A long, short-term memory model could be built to consider this.

Note: During the final few moments I ran into issues with my developing environment and setup. I'm unable to run or test anything currently, but as soon as I am able to I will push changes and the updated rnn.py program to this repository.
