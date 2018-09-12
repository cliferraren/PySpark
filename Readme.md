## PySpark
![png](Basics/data/pyspark.jpg)


Here, I learned how to use Spark from Python! Spark is a tool for doing parallel computation with large datasets and it integrates well with Python. PySpark is the Python package that makes the magic happen. I used this package to work with data starting from the basics.

Basics(https://github.com/cliferraren/PySpark/tree/master/Basics):
 1. [Working with CSV](https://github.com/cliferraren/PySpark/blob/master/Basics/Working_with_CSV_file.ipynb)
 2. [Working with JSON](https://github.com/cliferraren/PySpark/blob/master/Basics/Working_with_JSON_file.ipynb)
 3. [Filtering of Data](https://github.com/cliferraren/PySpark/blob/master/Basics/Apply_Filtering.ipynb)
 4. [Filtering of Data with CSV](https://github.com/cliferraren/PySpark/blob/master/Basics/Apply_Filtering_SecondPart.ipynb)
 
Demo Analysis:
 1. [RainFall Analysis](https://github.com/cliferraren/PySpark/blob/master/Basics/Rainfall_Analysis.ipynb)
 2. [Bigfoot Sightings](https://github.com/cliferraren/PySpark/blob/master/Basics/Bigfoot_Sightings_Analysis.ipynb)


I aslo learn to wrangle this data and build a whole machine learning pipeline to predict whether or not flights will be late. Get ready to put some Spark in your Python code and dive into the world of high performance machine learning! 

 To accomplish this, we need:
 1. [Simple Python library](https://pypi.python.org/pypi/citipy)
 2. [OpenWeatherMap API](https://openweathermap.org/api)
 3. Use the Matplotlib and Seaborn libraries
 
Our objective is to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Our final notebook must:

* Must have selected **at least** 500 randomly unique (non-repeat) cities based on latitude and longitude.
* Perform a weather check on each of the cities using a series of successive API calls. 
* Include a print log of each city as it's being processed with the city number, city name, and requested URL.
* Save both a CSV of all data retrieved and png images for each scatter plot.
