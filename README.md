# Mortality Analyzer and Predictor

This dashboard, hosted by Heroku, allows a user to view state specific noncancerous mortality data the was collected and 
published by the Centers for Disease Control and Prevention (CDC). The dataset, Chronic Disease Indicators (CDI), contains
over 100,000 data points. This file had to be sorted for valid data that pertained to diseases with mortality rates. The
data was processed and converted to graphs for the user to visualize. The user is able to see trends with the diseases
and is even able to see mortality rates for a future year given the current trends.

What was learned:
* This dashboard required a variety of Python libraries: Numpy, Pandas, SKLearn, Matplotlib, Ipywidgets to be able to process
and visualize.
* Uploading to Heroku with Voila was a challenge with the libraries that visualized the data.
* Although computers can process incredible amounts of data, it may not catch data points that 
contain errors as a result of the way the data was entered.

What can be improved:
* The dashboard is very basic and there are a variety of tools that could be use to enhance it, including: JavaScript with React and D3,
or Python with Flask or Django. There are other webframeworks that could be used as well.
* Only a small fraction of the data was processed and visualized. Starting at over 100,000 data points, the final dataset only contained
a few hundred to thousand points.
