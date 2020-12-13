# Air-Quality-Counter
A real-time air quality counter based on https://www.iqair.com/'s API, updates every 10 seconds, with odometer animation.

Currently being used on https://livecounts.winsdominoes.com/air-quality.

## About

This project was originally created to test the AirVisual (IQAIR) API with real-time information. But then I decided to make a full on site and use it to check the air quality in any city that is supported by the AirVisual API.

### How do I use this?

Go to https://livecounts.winsdominoes.com/air-quality and then type the city, the state and the country name in the Input section of the page then click submit, you will see the odometer numbers counting up and down updating every 10 seconds.

### How do I install this?

First, you need to make an AirVisual API key which is at https://iqair.com/dashboard and click API, then create an API key. Second, download the project from Github and open the index.html file. Copy that key and add it into this part of the index.html:  

//apikey for airvisual api

var apikey = "";

Finally, open the index.html file and you are done!
