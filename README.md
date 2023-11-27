
Weatherapi
Building a Backend API for Weather Forecast using Python as the Programming language and Flask as the framework and testing the api with postman

For execution of script follow these steps
#step1
run this script in the vs code make sure you have installed python on your device and also make sure the required libraries are installed like flask,requests
#step2
after hitting the run button in the terminal you will see the base url like http://127.0.0.1:5000 just open this in your browser.
by default this link is selected when you open this link you will see 404 error to fetch the weather you have to append this base url with api endpoint
/weather?location=city name #replace the city name with the name of the city of which you have to get the weather data
add this above url with city name to base url and then you will get the weather data ex:-http://127.0.0.1:5000/weather?location=bengaluru
Thats it now you can see the json file NOTE:-make sure your script is running parallely in vs code

![image](https://github.com/Vaibhavisooda/Vaibhavisooda/assets/150245603/71e73f89-b955-49ba-8341-d23835a42858)

Screenshots to execute this

![image](https://github.com/Vaibhavisooda/Vaibhavisooda/assets/150245603/c2e52787-a0b6-4ec1-b572-479a9f997843)
Second pic showing adding api endpoint to get the data after opening base url in browser

![image](https://github.com/Vaibhavisooda/Vaibhavisooda/assets/150245603/08afdb5a-522d-4dea-8d27-f3867079f7bf)

output
![image](https://github.com/Vaibhavisooda/Vaibhavisooda/assets/150245603/ce43225a-99bf-4ef3-b75b-ecefc08a3010)

following all the steps you will get the result in json file you can also change the city name and try with other locations
after getting the output copy that url in your browser and test the api with postman

![image](https://github.com/Vaibhavisooda/Vaibhavisooda/assets/150245603/6cd93dcb-4636-4390-b530-f96851b2ad9f)









