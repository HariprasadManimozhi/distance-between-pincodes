# How far is my locality?

## Objective:
Find the distance of all localities in a city from a desired locality.

## Tools:
* Python
* Geocoding libraries - pgeocode, geopy, geocoder
* Open data of location from govt websites 

## Steps:
* This can approached in two ways by computing distance between using 
    * **pincodes**
    * **longtidues-latitudes**
* Three methods have been tried to converge at better results:

    1. **pgeocode** - Postal code geocoding and distance calculations
    2. **geopy** - Distance between localities using longitude & latitude
    3. **geocoder & geopy** - Get Latitude & longitude of localities & compute distance using geopy

## References:
Included in jupyter notebook
