# python-api-challenge
Module 6 Challenge


## Part 1: WeatherPy
### To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature
![Screenshot 2023-10-30 181930](https://github.com/Samantha0Hall/python-api-challenge/assets/140672220/a2be148e-7b60-43c3-8f87-c02a718a9b6b)


Latitude vs. Cloudiness
![Screenshot 2023-10-30 182057](https://github.com/Samantha0Hall/python-api-challenge/assets/140672220/96c132a8-5ed2-479d-aed7-1f14fd9644dc)  

-----------------------------------

To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

![Screenshot 2023-10-30 182413](https://github.com/Samantha0Hall/python-api-challenge/assets/140672220/dc33c37b-c6f3-451c-87fb-b1205d666ee8)

![Screenshot 2023-10-30 182447](https://github.com/Samantha0Hall/python-api-challenge/assets/140672220/454c34d8-eef0-482f-a66b-58cde255e9db)

---------------------------------
## Part 2: VacationPy

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

![Screenshot 2023-10-30 183153](https://github.com/Samantha0Hall/python-api-challenge/assets/140672220/0f008ca6-d5eb-456a-99aa-d42901f2d99a)


Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature lower than 27 degrees but higher than 21
Wind speed less than 4.5 m/s
Zero cloudiness

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

![Screenshot 2023-10-30 183330](https://github.com/Samantha0Hall/python-api-challenge/assets/140672220/b21d96bb-a9a9-4485-bdca-87685e2a4774)

