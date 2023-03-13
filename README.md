# -2-year-Treasury-Yield-vs.-Fed-Funds-Target-Range---Upper-Limit-

Here's an example of how to plot both the 2-year Treasury yield and the Federal Funds Target Range's upper limit 
on the same chart using the pandas_datareader library and matplotlib:

This code retrieves the 2-year Treasury yield and the Federal Funds Target Range's upper limit from FRED using 
pandas_datareader and combines them into one DataFrame. The plot() function is then used to plot the two series on the same chart. 
The ax.set_xlabel(), ax.set_ylabel(), and ax.set_title() functions are used to set the labels for the x-axis, y-axis, and chart title, respectively. 
Finally, the ax.legend() function is used to add a legend to the chart.

The slope represents the change in the Federal Funds Target Range's upper limit for a one-unit increase in the 2-year Treasury yield, while the intercept represents the value of the Federal Funds Target Range's upper limit when the 2-year Treasury yield is 0. You can use the model.predict() function to predict the Federal Funds Target 
