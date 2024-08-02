# Archive of historical data on number of tests and positivity rate for COVID-19 in Germany

01.08.2024, Dominic Wild

## Description

The dataset contains data about the testing volume and positivity rate during COVID-19 in Germany. The timeframe reaches from 2020, week 10 to 2022, week 33. It can be found at [GitHub](https://github.com/NeWildeSache/MoSD-Exam/blob/master/data/preprocessed_data/germany_weekly_testing_data.csv) and [Zenodo](https://zenodo.org/doi/10.5281/zenodo.13172105).

## Columns

- tests_done [numeric]: number of tests done within week
- positivity rate [numeric]: 100 x number of new confirmed cases/number of tests done per week
- year [numeric]: year of sample 
- week [numeric]: week of sample
- time [numeric]: year + week/53, comparable

## Origin

The dataset is a subset of the dataset `weekly_testing_data_EUEEAUK_2022-09-15` published by the European Centre for Disease Prevention and Control. It can be found in the folder `raw_data` or at their official [website](https://www.ecdc.europa.eu/sites/default/files/documents/weekly_testing_data_EUEEAUK_2022-09-15.xlsx). Provenance information can be found in the file `2021-01-13_Variable_Dictionary_and_Disclaimer_weekly_testing_data_EUEEAUK_1` which is also located in the `raw_data` folder or at the same website as the dataset.