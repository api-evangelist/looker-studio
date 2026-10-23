---
title: "Introducing TimesFM 3.0 with multivariate time-series forecasting in BigQuery"
url: "https://cloud.google.com/blog/products/data-analytics/bigquery-timesfm-3-0-with-multivariate-time-series-forecasting/"
date: "2026-10-12"
author: "Haiyang Qi"
feed_url: "https://cloudblog.withgoogle.com/products/data-analytics/rss/"
---
Overview Since introducing zero-shot time-series forecasting in BigQuery with AI.FORECAST — initially powered by TimesFM 2.0 and later upgraded to TimesFM 2.5 — you have been able to generate forecasts directly in SQL without training or managing custom models. However, up until TimesFM 2.5, these foundation models were limited to univariate forecasting, predicting future values from the history of a single time series alone. In practice, most real-world forecasting problems are multivariate, where related targets and external drivers like weather, promotions, and holidays jointly shape future
