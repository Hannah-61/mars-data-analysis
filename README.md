# mars-data-analysis

This project demonstrates web scraping, data analysis, and visualization techniques applied to datasets related to Mars. The project is divided into two parts: scraping Mars news and analyzing Mars weather data.

# Table of Contents
Overview
Technologies Used
Dataset Details
Project Structure
Results

# Setup Instructions
Usage
Acknowledgments

# Overview
This project involves:

--Extracting Mars news titles and previews from a website.
--Scraping weather data from an HTML table and performing analysis to answer scientific questions.
--Visualizing trends in Mars weather, including temperature and pressure.

## Technologies Used
Python
Jupyter Notebook
Libraries: splinter, beautifulsoup4, pandas, matplotlib
Dataset Details

# Mars News
Titles and previews of news articles were scraped from the Mars News website.
--Mars Weather
Weather data was scraped from a table on the Mars Temperature Data Site.
The table includes:
id: Transmission ID
terrestrial_date: Earth date
sol: Martian day since landing
ls: Solar longitude
month: Martian month
min_temp: Minimum daily temperature in Celsius
pressure: Atmospheric pressure in Pa

# Project Structure
.
├── Starter_Code/
│   ├── part_1_mars_news.ipynb  # Scrapes Mars news titles and previews
│   ├── part_2_mars_weather.ipynb  # Scrapes and analyzes Mars weather data
│   ├── mars_weather_data.csv  # Cleaned weather data (output)
├── README.md  # Project description
Results

## Mars News
Scraped multiple news articles, each containing a title and preview text.

## Mars Weather Analysis
Temperature Trends: Identified the coldest and warmest months on Mars.
Pressure Trends: Found months with the highest and lowest atmospheric pressure.
Martian Year Length: Estimated the number of Earth days in a Martian year based on temperature cycles.

## Key visualizations include:
Average minimum temperature by Martian month.
Average atmospheric pressure by Martian month.
Minimum temperature trends over time to estimate a Martian year.

## Setup Instructions
-- Clone the repository:

git clone https://github.com/Hannah-61/mars-data-analysis.git
cd mars-data-analysis

-- Install dependencies:

pip install -r requirements.txt
(Add a requirements.txt file if not already present with necessary libraries: splinter, beautifulsoup4, pandas, matplotlib.)

-- Open the Jupyter Notebooks:

jupyter notebook
Run part_1_mars_news.ipynb to scrape Mars news and part_2_mars_weather.ipynb for Mars weather analysis.

-- Usage
Run the scraping scripts to collect Mars data.
Analyze the data and interpret the visualizations.
