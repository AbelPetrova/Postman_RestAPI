>[!NOTE] 
>**Work in progress**

# Postman_RestAPI 

Bellow are few API requests using Postman.

API provider: https://openweathermap.org/api

## Call current weather data


-- ***API request using lat and long coordinates for city***

![API call using lat and long coords.](https://raw.githubusercontent.com/AbelPetrova/Postman_RestAPI/main/Screenshots/Call%20current%20weather%20data.jpg)

:page_with_curl: JSON output [here](JsonOutputs/APIcallUsingLong&Lat.json).

_Details:_ An API call which shows the current weather data for Bucharest by using `lat` and `long` parameters. `Units` parameter has also been added in order to convert the temperature from Kelvin to Celsius units.



-- __*API request using name for city*__

![API call using name for city](https://raw.githubusercontent.com/AbelPetrova/Postman_RestAPI/main/Screenshots/CallUsingCityName.jpg)

:page_with_curl: JSON output [here](JsonOutputs/APIcallUsingCityName.json).

_Details:_ An API call which shows the current weather data for Nuuk city by using `q` parameter. Also `lang` parameter has also been added to get the output in Romanian language. 

 
## Call 5 day / 3 hour forecast data

![API call using name for city](https://raw.githubusercontent.com/AbelPetrova/Postman_RestAPI/main/Screenshots/APICall5day3hourForecastData.jpg)

:page_with_curl: JSON output [here](JsonOutputs/APIcall5day3hourForecastData.json).

_Details:_ An API call showing 3 day forecast data using `cnt` parameter which shortens the data from 5 days to 3 only. Additional `Units` and `lang` parameters has also been added. 






