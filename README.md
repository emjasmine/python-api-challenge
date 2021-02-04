# python-api-challenge
This respository contains code for two analysis:
    * Weather Analysis
        Using api.openweathermap.org, pulled weather data for a cities within a csv file and plotted the following:
        - Temperature (F) vs. Latitude
        - Humidity (%) vs. Latitude
        - Cloudiness (%) vs. Latitude
        - Wind Speed (mph) vs. Latitude

        Additionally, ran linear regression on each relationship, breaking the plots into a Northern/Southern Hemisphere view.

        Final output of this was saved as a csv file.
    
    *Vacation Analysis
        Using the csv file created as part of the weather analysis, performed the following:
        -Drop any cities in the csv file that did not meet all three of the following conditions:
            * A max temperature lower than 80 degrees but higher than 70
            * Wind speed less than 10 mph
            * Zero cloudiness
        -Using that new list of cities, find hotel/lodging within a radius of 5000 meter for each city.
        -Created a heat map based on humidity and add a layer showing the hotel data
