# web-scraping

# Overview

Purpose: To utilize full web-scraping and data analysis. Using HTML elements on a page, and parsing with Beautiful Soup we will analyze data from Mars news articles. 

# Resources
- Data Source: 
-[Mars News](https://static.bc-edx.com/data/web/mars_news/index.html)

-[Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) 
- Software: Python 3.9.13, Jupyter Notebook.

# Part 1: Scrape Titles and Preview Text from Mars News

File location: [web-scraping-codes/part_1_mars_news.ipynb](web-scraping-codes/part_1_mars_news.ipynb)

When running the code, we will be utilizing an automated browswer (Splinter) to visit the Mars news site. With Beautiful Soup, we were able to extract HTML Code to preview titles and text of news articles. 
We then stored the information into a list of dictionaries. 

# Part 2: Scrape and Analyze Mars Weather Data

File location: [web-scraping-codes/part_2_mars_weather.ipynb](web-scraping-codes/part_2_mars_weather.ipynb)

Utilizing Splinter, we visited Mars Temperature Data Site, and scraped the data using Beautiful Soup  to create a Pandas Dataframe that included information about Mars (terrestrial date, sol, ls, month, min temperature, and pressure). We ensured the columns had correct headings, and data types.

Analysis: 

Utilizing the data we scrapped, we answered the following questions:

How many months exist on Mars? 
How many Martian days' worth of data are there?
Which month, on average, has the lowest temperature? The highest? 
Which month, on average, has the lowest atmospheric pressure? The highest? 
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 

We then expored the DataFrame into a CSV file [Mars_weather_data](web-scraping-codes/Mars_weather_data.csv). 





