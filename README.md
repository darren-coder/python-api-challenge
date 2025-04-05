# python-api-challenge

# weatherPy
-This challenge was to make an API call to retrieve weather data from a randomly generated list of cities and make plots that show the linear relationship between latitude and various weather measurements. Random coordinates were created using numpy and then the nearest city to each coordinate was added to a list. Four plots were made showing the relationship latitude has to temperature, humidity, wind speed, and cloudiness. Next the list of cities was divieded into the northern and southern hemispheres. A seperate linear regression was then plotted for both northern and southern hemispheres showing the relationship latitude has on each of the four weather factors being considered, totalling 8 plots.

# VacationPy
-In this part of the challenge, each of the cities generated in the WeatherPy portion was plotted using hvplot, using humidity as the size of the points. Then the cities were narrowed down to my preferences and using geoapify, the closest hotel was found. Some cities didn't have hotels nearby.  Finally, all of my preferred cities were plotted using hvplot. I think my destination will be the Maximus Inn in Sechura, Peru.