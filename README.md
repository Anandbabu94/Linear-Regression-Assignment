# 🚲 Linear Regression Assignment - Bike Sharing Demand Prediction

This repository contains a Jupyter Notebook for a multiple linear regression model aimed at predicting the **demand for shared bikes** in the US market. The project is based on a dataset provided by BoomBikes, a US-based bike-sharing service that has seen a dip in revenues due to the COVID-19 pandemic.

## 📌 Problem Statement

BoomBikes wants to understand the **factors influencing daily demand for shared bikes** so they can prepare and adapt their post-pandemic business strategy. A reliable predictive model will help them:

- Forecast future demand.
- Identify key drivers of bike rentals.
- Design informed business strategies to stay competitive.

## 🎯 Business Goal

Build a **multiple linear regression model** to:

- Identify significant variables affecting bike rental demand.
- Understand how each feature influences the total demand.
- Predict future demand based on meteorological and seasonal data.

## 📊 Dataset Overview

The dataset contains daily-level records of bike-sharing demand along with various independent variables such as:

- Season
- Weather situation
- Temperature, humidity, wind speed
- Day of the week, year, and month
- Count of casual and registered users

The target variable is:

- `cnt`: Total count of bike rentals (casual + registered)

> Note: Do **not** use `casual` and `registered` as independent variables since they are components of the target variable.

## 🧹 Data Preparation Guidel
