# OpenRice-Webscraping
This webscraping project utilized BeautifulSoup and Selenium to scrape OpenRice.com. I conducted exploratory data analysis (EDA) on HK's most popular restaurants, taking a deeper look at popular districts and food categories. The dataset scraped has a total of 250 restaurants, as OpenRice.com only allowed a maximum of 17 pages to be scraped.

# Project Aim
- Explore the dataset using pandas.
- Create data visualizations using matplotlib and seaborn.
- Perform data analysis to explain the data visualizations that have been created.

# Files
- README.md
- Top Restaurants in HK based on Openrice - EDA.ipynb
- Top Restaurants in HK based on Openrice - Webscraping, Creating the CSV File.ipynb
- Web scraping Project - Openrice.ppt
- openrice_raw_dataframe.csv

# Project Steps
## Scraping OpenRice.com
1. Import packages and install chromedriver for selenium.
2. Open the URL you would like to scrape.
3. Create the webscraping function and run it.
4. Create the dataframe to save the scraped information and import it to a csv file ('openrice_raw_dataframe.csv').

## Exploratory Data Analysis
1. Import packages and the dataset 'openrice_raw_dataframe.csv'.
2. Data pre-processing (handling null values, adding new columns).
3. Conduct EDA using matplotlib and seaborn.
4. Insight analysis and potential action plan based on findings.
