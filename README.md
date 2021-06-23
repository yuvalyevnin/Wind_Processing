# A Deep Learning Model for Improved Wind and Wave Forecasts

This repository is the code for a paper by the same name, currently under review at Geophysical Research Letters journal. Pre-print available at: https://www.essoar.org/doi/abs/10.1002/essoar.10506907.1
If you are this work for publication, please cite:
>Yevnin, Y. and Toledo, Y., 2021. A Hybrid Deep Learning Model for Improved Wind and Wave Forecasts.

## Description

This work presents a deep learning model improving the wind forecast, which is consequently used as a pre-process to improve wave forecasting. The novel approach of combining deep learning and classical forecasting models is tested over the Mediterranean Sea, and results in ~$10% improvement in both wind and wave forecasts RMSE over the current operational model. This significant improvement is even more substantial when examining the local region of the Aegean Sea during May to September, when the Etesian wind is dominant, improving wave height forecasts by over 35%.

## Getting Started

Code is available in [this notebook](https://github.com/yuvalyevnin/Wind_Processing/blob/master/Final.ipynb). Example of data is available as well, but it is recommended to download full data.

### Dependencies

Downloading the full data from ECMWF requires registering, installing and configuring [cdsapi](https://cds.climate.copernicus.eu/api-how-to)

## Authors

Yuval Yevnin ([yuval.yevnin@gmail.com](https://cds.climate.copernicus.eu/api-how-to)) and Yaron Toledo
