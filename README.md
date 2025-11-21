# COVID-19 Monte Carlo Forecast

This project implements a **data-driven Monte Carlo simulation** to forecast COVID-19 new cases for U.S. states using historical case data. The simulation is directly linked to your dataset, allowing state-level projections with uncertainty estimates.

## Features

* Uses historical `new_cases` per state to compute growth rates.
* Monte Carlo simulation introduces random variation for realistic forecasts.
* Handles weekly datasets and small state histories.
* Produces **mean forecast curves** and **90% confidence intervals**.
* Supports plotting forecasts for individual states or all states at once.
* Fully compatible with **Google Colab** and datasets mounted from Google Drive.

## How to Use

1. Mount your Google Drive in Colab and provide the path to your CSV dataset.
2. Run the simulation and plotting functions:

   * `plot_state_forecast("MS")` — forecast for a single state
