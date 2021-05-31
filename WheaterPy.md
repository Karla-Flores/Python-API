## WheaterPy

The aim is to visualize the weather of 500+ cities across the world at varying distances from the equator. The data were randomly selected from [OpenWeatherMap API](https://openweathermap.org/api), where detailed information about cities and their latitude, longitude, maximum temperature, humidity, cloudiness, wind speed, country, and a date was retrieved.

<img width="869" alt="Screen Shot 2021-05-30 at 10 10 16 PM" src="https://user-images.githubusercontent.com/77529968/120134483-d1d9d780-c193-11eb-8d38-891b858515a4.png">

The first objective is to build a series of scatter plots to show the following relationships:<br>
<ul>
<li>Temperature (F) vs. Latitude</li>
<li>Humidity (%) vs. Latitude</li>
<li>Cloudiness (%) vs. Latitude</li>
<li>Wind Speed (mph) vs. Latitude</li>
</ul>

The second objective is to run a linear regression on each relationship separating them into Northern Hemisphere and Southern Hemisphere
<ul>
<li>Northern Hemisphere - Temperature (F) vs. Latitude</li>
<li>Southern Hemisphere - Temperature (F) vs. Latitude</li>
<li>Northern Hemisphere - Humidity (%) vs. Latitude</li>
<li>Southern Hemisphere - Humidity (%) vs. Latitude</li>
<li>Northern Hemisphere - Cloudiness (%) vs. Latitude</li>
<li>Southern Hemisphere - Cloudiness (%) vs. Latitude</li>
<li>Northern Hemisphere - Wind Speed (mph) vs. Latitude</li>
<li>Southern Hemisphere - Wind Speed (mph) vs. Latitude</li>
</ul>


### Observable Trends
 
<ul>
<li>The maximum temperature versus latitude indicates that places closer to the equator line experience higher temperatures. As you move towards the poles, the temperature drops gradually.</li><br>

  ![Screen Shot 2021-05-30 at 10 36 08 PM](https://user-images.githubusercontent.com/77529968/120136194-71e53000-c197-11eb-8d83-11b8447ed532.png)

<li>Maximum temperature vs. Latitude in Northern Hemisphere shows a high negative correlation -0.81, and the r-square is 0.66, which suggests the tendency toward the poles. The data points are concentrated well around the regression line, indicating a good fit. On the other hand, the Southern Hemisphere's plot has a positive correlation of 0.74, and the r-square is 0.55; the observation is similar.</li><br>
  
  ![Screen Shot 2021-05-30 at 10 46 56 PM](https://user-images.githubusercontent.com/77529968/120136978-f5535100-c198-11eb-8544-dfcd667787a6.png)
  
  ![Screen Shot 2021-05-30 at 11 20 12 PM](https://user-images.githubusercontent.com/77529968/120139202-98a66500-c19d-11eb-9801-15e204ba8146.png)

<li>There is no correlation between Latitude and humidity, which the graphics Northern Hemisphere - Humidity (%) vs. Latitude and Southern Hemisphere - Humidity (%) vs. Latitude corroborate. The r-square values are in  Northern Hemisphere is 0.0 and Southern Hemisphere is 0.04; these values are so low that they confirm a poor correlation.</li><br>
  
  ![Screen Shot 2021-05-30 at 11 28 19 PM](https://user-images.githubusercontent.com/77529968/120139738-baecb280-c19e-11eb-890c-81225d878b0d.png)
  
  ![Screen Shot 2021-05-30 at 11 29 10 PM](https://user-images.githubusercontent.com/77529968/120139790-d8ba1780-c19e-11eb-8442-b48482febc24.png)

<li>There is no correlation between Latitude and wind speed, which the graphics Northern Hemisphere - Wind Speed (kph) vs. Latitude and Southern Hemisphere - Wind Speed (kph) vs. Latitude corroborate. The r-square values are in Northern Hemisphere 0.02 and Southern Hemisphere 0.07; these values are so low that they confirm a poor correlation.</li><br>
  
  ![Screen Shot 2021-05-30 at 11 41 09 PM](https://user-images.githubusercontent.com/77529968/120140620-85e15f80-c1a0-11eb-9b99-e8360e231c08.png)

  ![Screen Shot 2021-05-30 at 11 41 30 PM](https://user-images.githubusercontent.com/77529968/120140645-91348b00-c1a0-11eb-99f7-4d264309f44a.png)

  
  
