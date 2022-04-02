# Web-Scraping-Project

This is a data collection and storage project, the aim was to scrape only those features of text data which are required as input in other key projects.
For this project, key features of data have been extracted from multiple news websites so that the data can be used later on for
Sentimental Analysis and Visualization Project. 

Websites scraped are "Times Of India", "News 18 India", "Indian Express" etc.
I have scraped news headlines and URL's separately and stored as csv file as "Scraped_headlines.csv" and "Scraped_URL's.csv ". 

Scraping TOI was easy compared to other sites such as "Indian Express", where headlines were in different pages.
For accessing different pages I created a for loop and defined a function to directly extract headlines as well as URL's by using list indexing method. 

Libraries used - Requests, BeautifulSoup, Pandas. 
