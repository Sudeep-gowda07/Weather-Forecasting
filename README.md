# Weather-Forecasting

Built this project using HTML , CSS and JavaScript .

i'have used OpenWeatherMap API to get the weather details of the user entered city or user's current location.

I used vanilla JavaScript to create this weather app. In the JavaScript file, I got the user entered city name and sent a get request to an OpenWeatherMap API with passing the city name. If the user clicked on the “Get Device Location” button then first I checked the user browser supports geolocation API or not.

If it’s supported, I got the current latitude and longitude of the device and sent these coordinates to the OpenWeatherMap API. After I got an object as a response from the API then I displayed the property value to a particular HTML element. At last, using the id value that API provides us, I showed the custom weather icon/image according to the weather condition.


In this weather app , we can get the weather details of a particular city by entering the city name or we can also get our location weather details by clicking on the "Get device Location" button . if we entered an invalid city name then there is shown an error message.

we can get many weather details in this app like temperature in celcius, and humidity.


NORMAL VIEW OF THE APPLICATION IINTERFACE :


![normal view](https://user-images.githubusercontent.com/71512769/179971517-583dd20b-430d-4f2c-bc3d-f5798cd463a5.png)

GETTING WEATHER DETAILS BY GIVING VALID INPUT:


![getting weather details](https://user-images.githubusercontent.com/71512769/179971732-8ec01029-6313-496b-9cac-cc61794629d3.png)


![goa sample](https://user-images.githubusercontent.com/71512769/179971745-5b87b645-97df-455f-ba34-373720192856.png)



GETTING DEVICE LOCATION:


![Get Device location](https://user-images.githubusercontent.com/71512769/179972124-d063fd7b-a477-414d-883f-968c059b357a.png)


IF WE PERMIT TO GIVE OUR DEVICE LOCATION :


![sample view](https://user-images.githubusercontent.com/71512769/179972689-c187756b-c44d-4944-bce1-5054ec6f6778.png)


IF USER DENIES TO GIVE LOCATION ACCESS:


![User Denied Location](https://user-images.githubusercontent.com/71512769/179972788-81fd2c39-b7a6-4d8e-b80f-69c063b1b887.png)



IF USER INPUTS INVALID CITY NAME :


![invalid location](https://user-images.githubusercontent.com/71512769/179972903-8d25c7c2-c11e-474f-9a7b-4a77939322d4.png)


SOME SAMPLE VIEWS:

![Delhi](https://user-images.githubusercontent.com/71512769/179972993-03d3f2f4-e892-4994-a41b-4e75f5c9608e.png)


![New York](https://user-images.githubusercontent.com/71512769/179973015-d39ead89-5ebc-45b8-9fe5-18bea8769b57.png)


![ALASKA](https://user-images.githubusercontent.com/71512769/179974317-f5af428c-d91e-43e5-b5a2-780b29c49b25.png)


![NIGERIA](https://user-images.githubusercontent.com/71512769/179974335-55111f9d-0d60-467a-b623-0babc7989dd8.png)
