# Solar Power Generation Data Analysis

This repository gives an analysis of 34 days of solar power plant data, as found at:

> [Solar Power Generation Data](https://www.kaggle.com/datasets/anikannal/solar-power-generation-data) kaggle.com

## Goal and Results

The goal is to investigate the data to answer the following questions:

1) Can we predict daily power yield given a weather prediction?
2) Can we identify underperforming power inverters?
3) Can we predict when a power inverter will underperform?

General results are as follows:
1) We can accurately predict power generation given a days irradiation (sunlight intensity) measurements.
2) We can identify when a power inverter underperforms based on current irradiation measurements.
3) We cannot predict when an inverter will have an under-performning interval based on recent power performance.

Analysis is primarily on powerplant 1 data.

## Contents
The work is written in R markdown. The contents are as folows:

The data (power yields and weather sensors for two plants) -
```
Powerplant Data
```

Cleans the data (run first) -
```
pp-clean-data.Rmd
```

Investigates how to predict power-yield for a single time interval -
```
pp-power-regression.Rmd
```

Forcasts daily power yield given irradiation measurements -
```
pp-yield-forcasting.Rmd
```

Identifies when low power-yield occures, reports methods used to try to predict low power-yield, and investigates correlation of performance between different inverters -
```
pp-find-fail.Rmd
```
