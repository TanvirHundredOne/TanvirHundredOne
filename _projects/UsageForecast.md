---
layout: post
title: UsageForecast
description: Forecasts Service Usage, Anomalies and Peak Usage
---

* Forecast service volume, total traffic based on locations(i.e Districts, Upozilla etc.).
* Developed using [TFT](https://unit8co.github.io/darts/generated_api/darts.models.forecasting.tft_model.html) model and predicts hourly forecast.
* The system is run using Airflow automated Scheduler to serve daily prediction business teams.
* For fastival seasons, seperate system is developed to find peak usage using [Prophet](https://facebook.github.io/prophet/) to predict daily peak usage in those seasons.