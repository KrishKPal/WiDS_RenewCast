# RenewCast: Hourly Solar Power Forecasting with Machine Learning

RenewCast is an end-to-end machine learning project for forecasting solar power generation hour by hour. You will work with weather and solar generation data, engineer time-series features, train and compare several forecasting models, monitor how their performance drifts as conditions change, and present the final system as a dashboard.

The project is built so that you touch every stage of a real ML workflow: data, features, models, evaluation, monitoring and presentation.

A 5-week guided project under Winter of Data Science, IIT Bombay.

Mentor: Krish Kumar Pal

## What you will build

- A forecasting pipeline that predicts hourly solar power from weather and time features
- A comparison of several models against a simple baseline
- A drift analysis showing how model performance changes over time
- A Streamlit dashboard that presents the forecasts and results

## Tech stack

Python, NumPy, Pandas, Matplotlib, scikit-learn, Streamlit

## Plan

Week 1: ML fundamentals. Python, NumPy and Pandas refresher, supervised learning, train-test split, regression metrics, scikit-learn basics.

Week 2: Data and features. Exploring the dataset, time-series structure, feature engineering (lags, hour of day, seasonality), and a baseline persistence model.

Week 3: Modelling. Linear regression, random forest, gradient boosting, time-series cross-validation, hyperparameter tuning.

Week 4: Evaluation. Model comparison, error analysis with MAE and RMSE, drift monitoring, performance under changing conditions.

Week 5: Dashboard and wrap-up. Streamlit dashboard, final refinement, an optional extension, report and presentation.

## Outputs

By the end of the project you will have a working solar forecasting pipeline, a model comparison report, a drift analysis and a dashboard you can demo.

## Repository structure

- week1/ : ML fundamentals material
- week2/ to week5/ : weekly notebooks and instructions (added as the project proceeds)
- data/ : dataset and data description
- src/ : reusable code for the pipeline
- app/ : Streamlit dashboard
- report/ : final report and slides

## Setup

Install Python 3.10 or newer, then install the libraries with:

`pip install numpy pandas matplotlib scikit-learn streamlit jupyter`

You can also use Google Colab for everything except the dashboard.

## Data

- **Source:** [OPSD Time Series — 2020-10-06 release](https://data.open-power-system-data.org/time_series/2020-10-06/)
- **Original data:** German solar generation from the `DE_solar_generation_actual` column, measured in MW.
- **Time standard:** UTC.
- **Coverage:** The source release covers the period from 2015 to mid-2020. The actual usable range depends on the available observations.
- **Attribution:** Open Power System Data, *Data Package Time series*, version 2020-10-06. [DOI](https://doi.org/10.25832/time_series/2020-10-06).

Review the [OPSD legal notes](https://open-power-system-data.org/legal/) and applicable [ENTSO-E terms](https://transparency.entsoe.eu/) before redistributing the underlying observations.
