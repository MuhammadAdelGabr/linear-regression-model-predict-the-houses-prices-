# Linear Regression Model for House Price Prediction

In this tutorial, you'll learn how to create a machine learning linear regression model to predict house prices. The dataset used in this project contains various features like the average income of the area's residents, the average age of houses in the area, and more. The goal is to predict the price of a house based on these parameters.

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Dataset Overview](#dataset-overview)
3. [Installation](#installation)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Model Building](#model-building)
6. [Predictions](#predictions)
7. [Model Evaluation](#model-evaluation)


## Problem Statement
A real estate agent in the USA wants to predict house prices in different regions. The agent provided a dataset, and you decided to use a linear regression model to estimate the house prices. This project aims to create a model that helps the agent predict what a house would sell for, given certain parameters.

## Dataset Overview
The dataset contains 7 columns and 5,000 rows in CSV format. The data consists of the following features:

*'Avg. Area Income': Avg. Income of residents of the city house is located in.
* 'Avg. Area House Age': Avg Age of Houses in same city
* 'Avg. Area Number of Rooms': Avg Number of Rooms for Houses in same city
* 'Avg. Area Number of Bedrooms': Avg Number of Bedrooms for Houses in same city
* 'Area Population': Population of city house is located in
* 'Price': Price that the house sold at
* 'Address': Address for the house

## Installation
To set up the project, ensure you have Python installed. Use the following command to install the required libraries:

```bash
pip install -r requirements.txt
