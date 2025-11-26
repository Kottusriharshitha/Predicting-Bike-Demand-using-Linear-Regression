# Bike Sharing Demand Prediction – Linear Regression Model

This repository contains a **multiple linear regression model** designed to predict daily bike demand in an urban bike-sharing system. The model leverages historical usage patterns and environmental factors to help stakeholders understand demand dynamics and make data-driven operational decisions.

---

## Overview

The objective of this project is to build a forecasting model that predicts the **total number of bikes rented per day**. Using a variety of independent variables—from weather conditions to seasonal indicators—the model provides insights that can support:

* Inventory and fleet management
* Resource planning
* Service availability optimization
* Strategic decision-making for new or existing markets

A linear regression approach was chosen for its interpretability and effectiveness in understanding variable relationships.

---

## Dataset

The project uses **day.csv**, which contains daily aggregated bike-sharing data with the following fields:

* **instant**: Record index
* **dteday**: Date
* **season**: Season (1: spring, 2: summer, 3: fall, 4: winter)
* **yr**: Year (0: 2018, 1: 2019)
* **mnth**: Month (1–12)
* **holiday**: Whether the day is a holiday
* **weekday**: Day of the week
* **workingday**: 1 if the day is neither a weekend nor a holiday, otherwise 0
* **weathersit**:

  * 1: Clear, Few clouds, Partly cloudy
  * 2: Mist and cloudy conditions
  * 3: Light snow or light rain
  * 4: Severe weather (heavy rain, ice pellets, fog, snow)
* **temp**: Normalized temperature
* **atemp**: Normalized “feels-like” temperature
* **hum**: Humidity
* **windspeed**: Wind speed
* **casual**: Count of casual users
* **registered**: Count of registered users
* **cnt**: Total rental bikes (casual + registered)

---

## Project Highlights

**Predicting Bike Demand Using Linear Regression**
This project develops a data-driven forecasting model to estimate bike demand in a bike-sharing system. Key steps include:

* Collecting and preprocessing historical bike rental data
* Exploring and engineering features related to weather, seasonality, and time
* Training a multiple linear regression model using scikit-learn
* Evaluating model performance using standard regression metrics

The resulting model enables operators to better understand factors influencing bike usage and to optimize operational planning. This leads to improved customer satisfaction, allocation of resources, and overall system efficiency.

---

## Technologies Used

* Python
* NumPy, Pandas
* Matplotlib, Seaborn
* Scikit-learn

---


## Output

The final output is a trained linear regression model capable of predicting daily bike demand and providing interpretable insights into how different factors influence rental patterns.
