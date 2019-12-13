# Machine-Learning-and-Statistics-Project#
Author: Shane Canny
Date: 12 Dec 2019
Project: Machine Learning and Statistics Module Project 2019, Analysis of the Boston House Price Data Set.

Project Plan;

1.	Use Decriptive Statistics to Describe the data Set
	a.	Pair Plots
	b.	Desciptive Data Set
2.	Infer if House prices Along river are different to ones not along river
	a.	Create two data sets for house prices along the river and not
	b.	Do descriptive stats along river and not
	c.	Do Plots Box and Normality plots
	d.	Then confirm by doing Anderson darling test
	e.	Do levenes test to derermine equal variance and explain based on data not normal
	f.	Do welsh test to determine equal medians
3.	Build Neural Network
	a.	First one with just inputs you feel may impact PRICE
	b.	Second one with all inputs
	c.	Third one with whitened data
	d.	At the end do descriptive statistics, levenes test and boxplot to show they are the same


The Jupyter Note Book outlines the statistical analysis completed as part of the Machine Learning and Statistics Module 2019 Project. Below is outlined the objectives that were achieved.

A number of objectives where set out within this project;

1. Describe the data within the Boston House Price Data set. Descriptive statistics in conjuction with statistical graphs were used to present an overview of the descriptive statistics of the Boston House Data Set.<br>

2. Infer whether there was a price difference between the median house price of houses along and away from the Charles River. Through the use of  data preparation and statistical analysis is was determined there was a statistical difference between the price of houses along and away from the River Charles. <br>

3. Predict the median house price based off the variables contained within the Boston House Data Set using neural networks. Three neural networks were used with different activation and optimizer functions. Each neural network was used to develop the next with reducing loss' with each iteration of the neural network, culminating with a third neural network that predicted the median house price as (21.25) compared to the median house price contained within the original data set of (21.2). A Welsh's t-Test was performed on the third neural networks predicted results with the original data. The result being there is no significant statistical difference between the median values of the predicted prices and the original prices.


Attached as a back up to this Jupyter Note Book is a word file which contains all the infered statistical analysis completed on a separate statistical analysis software application (Minitab) so generated results in python could be verified from an independent source.