# Solar Power Generation Data Analysis

This repository gives an analysis of 34 days of solar power plant data, as found at:

> [Solar Power Generation Data]([https://proceedings.mlr.press/v162/lundstrom22a/lundstrom22a.pdf](https://www.kaggle.com/datasets/anikannal/solar-power-generation-data) Kaggle.com

##Goal and Results

The goal is to investigate the data to answer the following questions:

1) Can we predict the power generation given a weather prediction?
2) Can we identify underperforming power inverters?
3) Can we predict when a power inverter will underperform?

Analysis is primaiely on Powerplant 1 data.

General results are as follows:
1) We can accurately predict power generation given a days irradiation (sunlight intensity) measurements.
2) We can identify when a power inverter underperforms based on current irradiation measurements.
3) We cannot predict when an inverter will have an under-performning interval based on recent power performance.

## Runnign the Code
The work is written in R markdown. To run other files, first run all blocks of code in:
'''
pp-clean-data.Rmd
'''
