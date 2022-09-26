# ConnorDawg_Youtube_API

## Overview of the Analysis

ConnorDawg is the second channel for a popular streamer, youtuber, and podcaster that mostly comprises
edited videos of his streaming content for the Youtube platform. The purpose of this analysis is to 
generate summary statistics for the views on ConnorDawg's channel and provide visuals as well.

This project uses the Google API with Youtube to access the JSON data and find the video viewcounts as of 09/26/2022.
Although the images and results below are dated, when the code is run it will update the charts with current data. 

## Results

* With the removal of the outlier, the mean and stdev lower from 5.68e+05 to 5.54+e05 and 3.79e+05 to 3.21e+05 respectively
* The quartiles remain similar since only one value is removed from the dataset.
* The new max value is 1.87e+06 when the outlier of 3.44e+06 is removed from the dataset.
* The dataset is heavily skewed right in both datasets.
* A majority of the view counts are below 4.35e+05 views, but some videos have views in the millions which skews the data. 

![Histogram Plots](/Resources/HistogramPlots.png "Histogram Plots")
![Stats With Outlier](/Resources/StatsWithOutlier.png "Stats With Outlier")
![Stats Without Outlier](/Resources/StatsWithoutOutlier.png "Stats Without Outlier")