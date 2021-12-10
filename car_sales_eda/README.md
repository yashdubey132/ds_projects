## Objectives

We are performing an exploratory analysis on data of car sales in order to understand the influence of various parameters such as *age*, *color*, *transmission* and *mileage* of a car. We will:

1. Deal with missing, duplicate and erroneous data.
2. Deal with outliers in order to ensure our analysis is generalized and not affected by them.
3. Look at summary plots such as histograms and boxplots to understand the distribution of values.
4. Understand correlations and find the factors that primarily affect price of a vehicle.

## Data

The dataset contains the following fields:
- `price`
- `model_year`
- `model`
- `condition`
- `cylinders`
- `fuel` — gas, diesel, etc.
- `odometer` — the vehicle's mileage when the ad was published
- `transmission`
- `paint_color`
- `is_4wd` — whether the vehicle has 4-wheel drive (Boolean type)
- `date_posted` — the date the ad was published
- `days_listed` — from publication to removal

## Libraries Used
- *pandas*
- *numpy*
- *matplotlib*
- *seaborn*
