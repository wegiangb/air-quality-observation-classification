  
Air Quality Observations Quality Control  

Description
Validating and removing errors outliers from surface air quality observations from individual sensors so that these observation can be compared to ECMWF's CAMS air quality forecasts. By clustering analysis on these observations more reliable observations can be identified. Enhancing these observations by attaching data about factors that affect air quality these observations can have more credibility about their accuracy. CAMS lacks credible surface air quality observations in many parts of the world, often in the most polluted area such as in India or Africa. Some observations are available for these areas from data harvesting efforts such as openAQ but there is no quality control applied to the data, and it is often not well known if the observations are made in a rural, urban or heavily polluted local environment. This information on the environment is important because the very locally influenced measurements are mostly not representative for the horizontal scale (40 km) of the CAMS forecasts and should therefore not be used for the evaluation of the CAMS model.

Completed for ECMWF European Centre for Medium Weather Forecast 2020 
and ESoWC 2020

Implementation 

Milestone 3 Classification of AQ Stations 

Aims 
1 Choose an upper bound of values and identify value over to be outliers
2 Choose a lower bound of values 
3 Choose an increment on measurements that is acceptable for both increasing and decreasing values 
4 Find How many stations don’t measure every 15 minutes through a day and when are these are
5 Find stagnant measurements that don't change over a chosen amount 

Parameters 
1 Higher bound
2 Lower Bound 
3 Increment over measurements 
4 Timestep of expected measurements 
5 The higher bound and lower bound that designate stagnant measurements  

Presentation results

The scripts utput to test_results.csv and monitoring_report.html
(There are examples of these in the github)

Python Scripts 



Dependencies

Pecos Package 

https://pecos.readthedocs.io/en/stable/overview.html
https://github.com/sandialabs/pecos

