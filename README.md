# Project 3 Bootcamp
Group submission for Project 3 

## Members
* Burnap, Sarah
* Dreyer, Jordan
* Liu, Ellen
* Supnet, Renz Carl
* Theeng, Pratishtha

## Overview
In today's world food prices have become a hot topic. While we are most concerned by the prices in our home country of the USA, we should also check in with our foreign friends! This project aims to aid other researchers in possibly identifying spikes in food prices and helping to correlate world events that cause those price changes.
### Purpose
To create a database to enable future research related to the topic of food prices in 36 specific countries. Practice manipulating and cleaning data to make it more accessible to a general audience. 

## Usage intructions
Due to the size of our dataset and how that translates to the final poduct we are not able to house the base CSV and the database.ipynb in GitHub even with Git LFS. 
*Best practise would be to run our file in it's entirety as this will generate the csv and database files not uploaded. Keep in mind, the API call will need around 20 minutes or more to run. 
*We have included a smaller csv to run analysis on named WLD_RTFP_country_2025-04-07.csv. Please use this for faster processing in our data. 
*Additionally, Dask allows for faster processing by using multiple cores and allowing the user to select between running the commands on memory or on disk, that generates an additional file and may need to be adjusted depending on your machines processing power. 

## Ethical considerations
### Data acquisition
Our dataset cross references and is published in the  World Food Programme (WFP) and Food and Agriculture Organization(FAO).

## References for Data Sources
* [Microdata Library](https://microdata.worldbank.org/index.php/catalog/4483/study-description)
* [Dataset API](https://microdata.worldbank.org/index.php/catalog/4509/data-api)
* [Source on time period inflation](https://www.files.ethz.ch/isn/111316/food_inflation_3609.pdf)
## References
The class AI tool and Claude Ai was used to help in troubleshooting of dask code. 
