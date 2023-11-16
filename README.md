# Module-11-Challenge
# Mars Web Scraping and Data Analysis Project

## Background

In this project, you will leverage your web scraping and data analysis skills to collect, organize, and analyze data related to Mars from two distinct sources: Mars News and Mars Weather. The project aims to enhance your ability to identify HTML elements, utilize automated browsing with Splinter, parse HTML with Beautiful Soup, and apply data analysis using Pandas.

## What You're Creating

This assignment comprises two technical deliverables:

### Deliverable 1: Scrape Titles and Preview Text from Mars News

**Instructions:**
1. Open the Jupyter Notebook named `part_1_mars_news.ipynb` in the starter code folder.
2. Use automated browsing to visit the [Mars News site](#) and inspect the page to identify elements to scrape.
3. Create a Beautiful Soup object to extract text elements from the website.
4. Extract titles and preview text of news articles.
5. Store results in Python dictionaries with 'title' and 'preview' keys.
6. Store dictionaries in a Python list.
7. Print the list in your notebook.
8. Optionally, store the scraped data in a file (to ease sharing the data with others) by exporting it to a JSON file.

### Deliverable 2: Scrape and Analyze Mars Weather Data

**Instructions:**
1. Open the Jupyter Notebook named `part_2_mars_weather.ipynb` in the starter code folder.
2. Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html).
3. Create a Beautiful Soup object to scrape data in the HTML table (avoid using Pandas read_html for skill improvement).
4. Assemble the scraped data into a Pandas DataFrame with columns including id, terrestrial_date, sol, ls, month, min_temp, and pressure.
5. Examine and convert data types if necessary (datetime, int, float).
6. Analyze the dataset using Pandas functions to answer specified questions.
7. Plot results as bar charts.
8. Export DataFrame to a CSV file.

**Questions Answered:**
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- Coldest and warmest months on Mars:
   - Find the average minimum daily temperature for all months.
   - Plot results as a bar chart.
- Months with the lowest and highest atmospheric pressure on Mars:
   - Find the average daily atmospheric pressure for all months.
   - Plot results as a bar chart.
- About how many terrestrial (Earth) days exist in a Martian year?
   - Consider Earth days elapsed during Mars' orbit.
   - Visually estimate by plotting daily minimum temperature.

**Data Output:**
- Exported data files are stored in the `data_output/` folder.
- CSV file: `mars_weather_data.csv`
