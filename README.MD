# 2020 Santa Clara County Airbnb Listing Exploratory Data Analysis

## Introduction

In this project, I analyzed the Airbnb listing data for Santa Clara County, California, United States and conducted exploratory data analysis to come up with three tips that will help potential visitors to Santa Clara County with booking their accommodations on Airbnb.com

## Files

- [calendar.ipynb](calendar.ipynb): Jupyter Notebook for analyzing the calendar data
- [listing.ipynb](listing.ipynb): Jupyter Notebook for analyzing the listing data
- [Matplotlib Practice.ipynb](Matplotlib%20Practice.ipynb): Practice code for learning to use the matplotlib package based on [this page](https://www.machinelearningplus.com/plots/top-50-matplotlib-visualizations-the-master-plots-python/#31.-Waffle-Chart)

## Installation

To ensure reproducibility of this analysis, the following Python packages and data should be used.  

### Python Packages

| Package    | Version |
| :--------- | ------: |
| numpy      |  1.17.2 |
| matplotlib |   3.1.1 |
| pandas     |  0.25.1 |
| seaborn    |   0.9.0 |
| cartopy    |  0.17.0 |
| uszipcode  |   0.2.4 |

### Data

2019 November version of the data for Santa Clara County Airbnb listings were used:

- [calendar data](http://data.insideairbnb.com/united-states/ca/santa-clara-county/2019-11-07/data/calendar.csv.gz)
- [listing data](http://data.insideairbnb.com/united-states/ca/santa-clara-county/2019-11-07/data/listings.csv.gz)

A shape file used for creating the base map of Santa Clara County:

- [shape file](https://prd-tnm.s3.amazonaws.com/StagedProducts/Small-scale/data/Boundaries/countyl010g_shp_nt00964.tar.gz)

This zipfile should be downloaded and extracted to a sub-folder named 'data' under the project working directory

## Conclusion

As the conclusion of my analysis, three useful tips for booking Airbnb in Santa Clara County are:

1. Fridays and Saturdays are most expensive days of the week; May to October are the more expensive months of the year; avoid these days and months if you can.
2. You can find listings that are relatively cheap but with high review scores in: **Cupertino, Morgan Hill, Mountain View, San Jose, and Sunnyvale**
3. Opt for listings without mandatory cleaning fees if you can.

A write-up of the analysis was published as a blog plots on medium.com and can be accessed [here](https://medium.com/@handeasy/3-tips-for-booking-airbnb-in-santa-clara-county-in-2020-486eb5241353).

Any feedback or comment is welcomed!
