<H1> Outlier Detection </H1>

<H6> Detecting and managing outliers in a dataset. </H6>

Plotly is used to plot a graph of the data.
See python3 file 'OfflinePlotlyTrace.py' -- You will need to pip install plotly.

<H5> Graph below of data </H5>

![alt tag](https://github.com/raglew/OutlierDetection/blob/master/dataplot.jpg)

<H5> Figure below indicating possible outliers</H5>

![alt tag](https://github.com/raglew/OutlierDetection/blob/master/outliers.jpg)

Python3 file DataStats.py can be used to print out stats.
Lowest value =  1.7
Highest value =  11.95
Average =  2.82
Median =  2.15
Q1 =  1.92
Q3 =  3.04
IQR =  1.12
Multiplier =  2.2
Min value =  0
Max value =  5.5
NB. Values less than min value and greater than max value are traditionally defined as outliers.

Python3 file OutlierDetection.py can be used to plot stats. See below.

<H5> Figure below indicating outliers</H5>

![alt tag](https://github.com/raglew/OutlierDetection/blob/master/maxminoutliers.png)

Expected different results. Are the values indicated as outliers really outliers? Method to detect outliers needs to be examined further. Perhaps another approach is needed.

Two approaches spring to mind.

1. Use percentiles instead of quartiles.
2. Range across data series captured from several data collections.

