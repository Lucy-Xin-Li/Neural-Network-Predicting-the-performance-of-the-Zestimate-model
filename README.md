# Using Neural Network Predicting the performance of the Zestimate model

As most of you know, Zillow has become a major force in real estate. Their model "Zestimate" aims to predict housing prices based on a variety of features. In this dataset of many properties in southern California, they provide how well the model predicted house prices. Specifically, they calculated the (log) error between their model estimate and the actual price given by:

$logerror = log(Zestimate) - log(actual)$

This means that if the logerror was greater than 0, the Zestimate overestimated the actual prices, and if it was less than 0 the Zestimate underestimated the price. The goal of this project is to write a neural network that will predict whether the Zestimate will over or underpredict the price given features of other houses.
