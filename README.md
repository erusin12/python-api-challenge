# python-api-challenge
Challenge 6
This challenge analyzes a large group of cities with varying distances from the equator.  Cities were selected at random and the weather data was obtained.  The cities list was exported to use in a second piece of the project.  
Four scatter plots were created.  The first was the max temperature vs latitude.  The data showed that higher max temperaatures existed near the equator.  The next plot was latitude vs humidity, which had a pretty scattered chart, though there was a cluster of high humidity points around a latitude of 70.  The next scatter plot had latitude vs cloudiness, which was relative scattered except for points at 0% cloudiness and 100% cloudiness.  The last scatterplot covered latitude and wind speed and there doesnt seem to be a pattern between the two.
Last  part consisted of creating linear regressions.  A function was created as the plots all use the same formula with different variables.  The comparisons were of max temp and latitude, latitude and humidity, latitude and cloudiness, and then latitude and wind speed.  These regressions were done with the points being place in groupings of Northern and Southern hemispheres.  Most of the regressions showed no correlation except for comparing max temp to latitude - the closer the latitude was to 0, the higher the max temp.

The next part of the challenge was to use this city data to find ideal locations to vacation and then use Geoapify to help map the data and locate hotels in ideal cities.
The data from the first part of the challenge was imported and then mapped out.  Guidelines for ideal weather conditions were used to get a list of cities and then we used Geoapify to search those cities for the near the cities and they were mapped out.

To create this repo, I had assistance from a tutor, study group, and internet resources for questions.
