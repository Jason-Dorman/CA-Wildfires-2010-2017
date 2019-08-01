# CA-Wildfires-2010-2017
A closer look at California Wildfires and their causes from 2010-2017

This project used data from Cal Fire's Redbooks. The data was only available for indivudual years in a pdf format so I used a python library to convert the pdf to a csv file and had to do some additional cleaning. Then each year was merged into a single dataframe for analysis. 

I used a seperate python library to get geocodes for each fire district using only the zipcode. 

I created a map to see where most fires happened in the state throughout the period. The map also displays power lines using shapefiles from the state energy commission.
