# Introduction
## Problem Brief
Predictive maintenance refers to the set of techniques used to determine the operational condition of a system and estimate the maintenance time frame using predictive models. This helps reduce the operational costs of maintenance and prevent untimely failures which could lead to extended downtimes.

An important aspect of predictive maintenance is failure prediction using historical data. Analysis of sensor and telemetry data can be used to predict the Time-To-Failure (TTF) of a system which allows for the planning of a maintenance schedule. This is particularly useful for aircraft manufacturers and operators.

The aim of this exercise is to describe the usage of statistical learning techniques to historical sensor measurement data to predict the future failures of engines. Machine learning techniques can be used to establish relationships between sensor measurements and historical failures. The goal is to make the following predictions:
1. The Time-To-Failure (TTF) of an engine.
2. Classify whether an engine will fail in a given time period.

## Data
The data used for this exercise is a subset of a larger dataset generated by Microsoft and consists of run-to-failure scenarios for a number of aircraft engines. The following data files were provided for building the predictive maintenance models:
1. train_selected.csv - contains the historical sensor measurements and failure data for multiple engines over cycles of operation
2. test_selected_ttf.csv - contains the historical sensor measurements and failure data for multiple en- gines at a randomly selected cycle of operation. This will be used to quantify the accuracy of the models.

## Problem Formulation
In order to achieve the goals of the exercise supervised learning techniques will be used to establish relationships between sensor measurements and historical failures. The two requirements of the problem will be formulated as follows:
1. Regression models to predict the continuous dependent variable TTF
2. Binary classification models to predict whether an engine will fail in a given time period.

## Development Environment
1. Integrated Development Environment with Visual Studio Code (1.62.3) and Python (3.9.1)
2. Data processing with Pandas (1.3.4) and Numpy(1.21.3)
3. Data visualisation with Seaborn (0.11.2) and Yellowbrick (1.3.post1)
4. Machine learning with Scikit_learn (1.1.dev0)
