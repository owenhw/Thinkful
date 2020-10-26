# Bikeshare Data Modeling

Supervised Learning Capstone Project

In this project I will use supervised learning techniques to identify which bikes within the Indego bike share program in Philadelphia are likely to become inactive.


### The Dataset

The data for this project comes directly from the company via their website. https://www.rideindego.com/about/data/. Trip data from the beginning of the program in Q2 of 2015 until Q2 of 2020 is available. Station data is also available including coordinates, number of bikes available and number of empty bikes available.

Per the website the data has undergone some cleaning already. Trips longer then 24 hours have been capped and trips less than 1 minute have been removed. The dataset is not provided as a complete file see https://github.com/owenhw/Thinkful/blob/master/Capstone%202:%20Supervised%20Learning/Merging%20Indego%20Data.ipynb for data compilation.

### Hypothesis

>H1<sub>0</sub>There are no significant differences between the populations of active and inactive bikes

>H1<sub>A</sub> There are significant differences in one or more variables betweent the populations of active and inactive bikes

### Challanges

Reshaping and aggregating the data. Feature engineering will be particularly important because this data is sourced in a trip-wise fashion rather than a bike-wise fashion.

