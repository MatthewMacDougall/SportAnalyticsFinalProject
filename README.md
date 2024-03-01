# NHL Playoff/Stanley Cup Predictor ML Project

This repository contains code and documentation for an NHL playoff/cup predictor ML project developed as part of a sports analytics course I took during my MSBA program. The project utilizes machine learning techniques to predict playoff outcomes and identify factors contributing to a team's success in the NHL postseason.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Collection](#data-collection)
3. [Data Analysis and Modeling](#data-analysis-and-modeling)
    - [Linear Regression](#linear-regression)
    - [Probit Regression](#probit-regression)
    - [Stanley Cup Prediction](#stanley-cup-prediction)
4. [Conclusion](#conclusion)

## Project Overview <a name="project-overview"></a>

The goal of this project is to analyze historical NHL data and develop machine learning models to predict playoff outcomes and Stanley Cup winners. The project focuses on exploring various team statistics from both the regular season and postseason to understand their impact on playoff success.

## Data Collection <a name="data-collection"></a>

The data utilized in this project is sourced from [Natural Stat Trick](https://www.naturalstattrick.com/), which provides comprehensive team statistics for both regular season and postseason NHL games. The project gathers data for multiple seasons to analyze trends and patterns over time.

## Data Analysis and Modeling <a name="data-analysis-and-modeling"></a>

### Linear Regression <a name="linear-regression"></a>

The project starts by exploring correlations between various team statistics and regular season points using heatmaps. Key offensive metrics such as Corsi For (CF), Goals For Percentage (GF%), and High Danger Chances For (HDCF) are identified as significant factors contributing to a team's regular season success. Linear regression models are then trained to predict regular season points based on these offensive metrics. The models demonstrate a high degree of explanatory power, with R-squared values indicating strong correlations between the selected variables and regular season points.

### Probit Regression <a name="probit-regression"></a>

Probit regression is utilized to predict the likelihood of teams making the playoffs based on regular season statistics. The analysis focuses on evaluating the impact of different team metrics on playoff qualification. The project explores models both with and without certain variables, such as "GF%" and "Points", to assess their effect on model performance. Additionally, precision-recall curves are utilized to evaluate model effectiveness in predicting playoff qualification.

### Stanley Cup Prediction <a name="stanley-cup-prediction"></a>

The project extends the analysis to predict Stanley Cup winners using machine learning techniques. Probit regression models are trained to predict the probability of a team winning the Stanley Cup based on postseason performance metrics. The project also explores techniques such as undersampling to address class imbalance issues in the dataset.

## Conclusion <a name="conclusion"></a>

The NHL playoff/stanley cup predictor ML project demonstrates the effectiveness of machine learning techniques in analyzing historical data and predicting playoff outcomes. The project highlights the importance of offensive and defensive metrics in determining a team's success in the regular season and playoffs. Further enhancements, such as feature engineering and advanced modeling techniques, could improve the accuracy of predictions and provide deeper insights into factors influencing playoff success in the NHL.
