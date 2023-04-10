# web-scraping-challenge

In this activity, I was requested to identify HTML elements on 2 webpages and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. 
After the web-scraping, I used Pandas to perform the data analysis, answering the following questions, among others:

* Average temperature by month:

![Average temperature](https://github.com/cami5326/scraping-challenge/blob/main/Mars%20Info/pictures/avg%20temperature%20by%20month.PNG)

* Average pressure by month:

![Average pressure](https://github.com/cami5326/scraping-challenge/blob/main/Mars%20Info/pictures/avg%20pressure%20by%20month.PNG)

* How many terrestrial (earth) days are there in a Martian year?

![terrestrial days](https://github.com/cami5326/scraping-challenge/blob/main/Mars%20Info/pictures/earth%20days.PNG)

* Scraped data transformed into a Pandas DataFrame:

**id:** the identification number of a single transmission from the Curiosity rover

**terrestrial_date:** the date on Earth

**sol:**  the number of elapsed sols (Martian days) since Curiosity landed on Mars

**ls:** the solar longitude

**month:** the Martian month

**min_temp:** the minimum temperature, in Celsius, of a single Martian day (sol)

**pressure:** The atmospheric pressure at Curiosity's location

![Pandas DataFrame](https://github.com/cami5326/scraping-challenge/blob/main/Mars%20Info/pictures/pandas.PNG)



