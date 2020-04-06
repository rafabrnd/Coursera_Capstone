# Coursera Capstone Project Report
# Finding the best location for a nightclub in the city of Copenhagen, Denmark

## Introduction/Business Problem

A multinational nightlife investment company who owns diverse bars and nightclubs would like to expand his business to the city of Copenhagen in Denmark. Diverse previous reports indicated that the most lively areas (areas where most bars & nightclubs) are located have the most amount of food traffic in the city during the night time. For this reason, the company would like to find areas of the city that are arealy established as go-to zones for the young party community. These areas would represent the perfect location for a new and exciting nightlife business. In this notebook I will cluster the different locations of the city of Copenhagen based on the most common venues in order to understand where the location of the new bar should be. 

## Data

In order to cluster the different neighborhoods of the city, I will harness the power of Foursquare location data to retrieve the information about the venues for each postal code. For this study I will use the post code data that is publicly avaliable at:
https://www.regionh.dk/english/about-the-capital-region/facts-about-the-region/Pages/Postal-codes.aspx . Here I will use BeautifullSoup package to scrape the data from the table followed by cleaning up using Pandas. Using Forsquare I will retrieve the most common venues for each location and cluster each neighborhood using Kmean. If a sucessfull clustering of the neighborhoods is achieved, other datasets such as the current average price for real estate in the different areas may be included in order to guide our stakeholders on the locations with the best possible return on investment. 
