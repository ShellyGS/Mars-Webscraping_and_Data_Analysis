# **Full Web-Scraping and Data Analysis - MARS**

This is an exercise on web-scraping using Python's libraries Splinter, BeautifulSoup, Pandas and Matplotlib. There are two tasks in this exercise.

### **Part 1: Scrape Titles and Preview Text from Mars News**
#### Steps followed 

1. Use automated browsing to visit the [Mars news siteLinks to an external site.](https://static.bc-edx.com/data/web/mars_news/index.html). Inspect the page to identify which elements to scrape.
1. Create a Beautiful Soup object and use it to extract text elements from the website
1. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures .

### **Part 2: Scrape and Analyze Mars Weather Data**
#### steps followed 
1. Use automated browsing to visit the [Mars Temperature Data SiteLinks to an external site.](https://static.bc-edx.com/data/web/mars_facts/temperature.html). Inspect the page to identify which elements to scrape. 
1. Create a Beautiful Soup object and use it to scrape the data in the HTML table.
1. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 
1. Examine the data types that are currently associated with each column. 
1. Analyze your dataset by using Pandas functions to answer the following questions:
   1. How many months exist on Mars?
   1. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
   1. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
      1. Find the average minimum daily temperature for all of the months.
      1. Plot the results as a bar chart.
   1. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
      1. Find the average daily atmospheric pressure of all the months.
      1. Plot the results as a bar chart.
   1. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
      1. Consider how many days elapse on Earth in the time that Mars circles the Sun once.
      1. Visually estimate the result by plotting the daily minimum temperature.
1. Export the DataFrame to a CSV file.

