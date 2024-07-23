# Mars Challenge

## Overview

This repository contains the Mars Challenge project, which involves web scraping data related to Mars news and weather, analyzing the data, and visualizing the results. The project is divided into two main parts:

1. Scraping Titles and Preview Text from Mars News
2. Scraping and Analyzing Mars Weather Data

## Technologies Used
* Python
* Splinter
* BeautifulSoup
* Pandas
* Matplotlib

## Project Structure
The project is structured as follows:
* part_1_mars_news.ipynb: Jupyter Notebook for scraping Mars news titles and preview texts.
* part_2_mars_weather.ipynb: Jupyter Notebook for scraping and analyzing Mars weather data.
* mars_weather_data.csv: CSV file containing the scraped Mars weather data.

## Part 1: Scraping Mars News

In this part, we:

1. Use automated browsing with Splinter to visit the Mars news site.
2. Scrape the titles and preview texts of the news articles using BeautifulSoup.
3. Store the results in a list of dictionaries and print the list.

## Part 2: Scraping and Analyzing Mars Weather Data
In this part, we:
1. Use automated browsing with Splinter to visit the Mars Temperature Data Site.
2. Scrape the data in the HTML table using BeautifulSoup.
3. Store the scraped data in a Pandas DataFrame.
4. Analyze the data to answer specific questions and visualize the results.
5. Save the DataFrame to a CSV file.

## Results
### Mars News
We successfully scraped and printed the titles and preview texts of the Mars news articles.

### Mars Weather Data
We analyzed the Mars weather data and found the following:

- The coldest month on Mars is the third month, with the lowest average minimum temperature.
- The warmest month on Mars is the eighth month, with the highest average minimum temperature.
- The month with the lowest atmospheric pressure is the sixth month.
The month with the highest atmospheric pressure is the ninth month.
- A Martian year is approximately 687 Earth days, as confirmed by plotting the daily minimum temperature.
