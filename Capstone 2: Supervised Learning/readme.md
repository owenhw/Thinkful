# Bikeshare Data Modeling

Supervised Learning Capstone Project

Modeling traffic and usage data of infrastructure is critical to making decisions about how to invest in and deploy infrastructure going forward. In a business case, predicting vehicle demand would help the program optimize revenue. The goal of this project is to predict traffic inflows and outflows from neighborhoods.


### The Dataset

The data for this project comes directly from the company via their website. https://www.rideindego.com/about/data/. Trip data from the beginning of the program in Q2 of 2015 until Q2 of 2020 is available. Station data is also available including coordinates, number of bikes available and number of empty bikes available.

Per the website the data has undergone some cleaning already. Trips longer then 24 hours have been capped and trips less than 1 minute have been removed. The dataset is not provided as a complete file see https://github.com/owenhw/Thinkful/blob/master/Capstone%202:%20Supervised%20Learning/Merging%20Indego%20Data.ipynb for data compilation.

### Hypothesies

> H1<sub>0</sub> There is no statistically significant variance in traffic flow based upon the time of day.
<br>H1<sub>A</sub> There is a statistically significant variance in traffic flow based upon the time of day.
<br>

> H2<sub>0</sub> There is no statistically significant difference in the difference in flow based upon the neighborhood.
<br>H2<sub>A</sub> There is a statistically significant difference in the difference in flow based upon the neighborhood.

### Challanges

Reshaping and resampling the data on a time interval.

