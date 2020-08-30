# Final-Project

## Introduction

### Description and Background

Buenos Aires is the capital of Argentina, and is a city with a high population. 

For this project I have scraped data from various data about Buenos Aires Territorial price. 

Then I used Foursquare API to get the common venues of the neighborhoods. 

Then using K-means clustering I clustered Buenos Aires Neighborhoods on the basis of the common venues.

This project is mainly made for territorial investor. As from territorial investor point of view, we want to invest in such places were the territorial prices are low and the facilities (shops, restaurants, parks...etc) and social venues are nearby.  


This project is targeted towards:
  * Territorial Investor who wants to know the territorial price in different neighbothoods in Buenos Aires. 
  * People interested in buying territorio in Buenos Aires for living. 

### Data Description
For the project we used the following data:
  * An excel file provided by the Buenos Aires government. ('http://cdn.buenosaires.gob.ar/datosabiertos/datasets/terrenos-valor-de-oferta/precio-de-terrenos-2018.xlsx') This excel file contained the list of territorial price for different neighborhoods in Buenos Aires.
  * Foursquare API to get the most common venues for each of the selected neighborhoods. https://foursquare.com/developers/apps.
  * The geopy.geocoders library to get the coordinates for each neighborhood in order to map it using the folium library, the coordinates were also used for the Foursquare API.
  * I designed the limit as 100 venue and the radius 1400 meters for each neighborhood from their given longitude and latitude information.

