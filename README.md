# Code Architecture

We will have 2 main classes:

## 1. Scraper

which will open the browser, scrape and gather the data from the website and return a dictionary of items for us

## 2. Report Generator

it will take that dictionary as an arg and create a report for us

# Script Goals

### Scraper

1. Run the browser
2. Go to amazon website
3. Look for our items links (scrape)
4. Enter our specific item name into search bar
5. Go through multiple pages (scrape the whole product on the list and get ALL links)
6. Loop through each link,, and get all the data from each product & store it in memory

### Report Generator

7. GenerateReport class will create a report based on our data (maybe a json file?)
