# Predicting the popularity of food tweets

Final exam project for the **Introduction to Machine Learning** course, held by Prof. Eric Medvet ([@ericmedvet](https://github.com/ericmedvet)) at the Univeristy of Trieste during the 2022-2023 academic year.

## Problem statement

It is reuqired to study a ML-based technique to predict potential popularity of a tweet that talks about *food*. The data is not provided, so the part about data collection has to be treated as well.

## Proposed solution

After collecting data with [Twitter APIs](https://developer.twitter.com/en/docs/twitter-api), we learn a dummy regressor, linear regressors, Regression trees and Random forests models and evaluate them in terms of *effectiveness* (measured throug the Mean Squared Error of the predictions) and *efficiency* (related to prediction times).

The best model results to be a *Random forest* with $100$ trees and $50$ maximum observations for each leaf node. At a little cost of *effectiveness*, even a single *Regression tree* achieve good results.

A detailed report of the study in can be found in the [.pdf](./relation/FoodTweetsPopularityPrediction.pdf) file inside the `./relation/` directory.
All the *R* code used in the present project, with the exception of those for the data retention, is available in the [.Rmd](./TweetPopularity.Rmd) file.