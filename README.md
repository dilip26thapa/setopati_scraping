# Illustration by Author
# Disclaimer: The goal of this post is only educational. Web Scraping is not encouraged, especially when there are terms and conditions against such actions.

The post is the fourth in a series of tutorials to build scrapers. Below, there is the full series:

HTML basics for web scraping
Web Scraping with Octoparse
Web Scraping with Selenium
Web Scraping with Beautiful Soup (this post)
The purpose of this series is to learn to extract data from websites. Most of the data in websites are in HTML format, then the first tutorial explains the basics of this markup language. The second guide shows a way to scrape data easily using an intuitive web scraping tool, which doesn’t need any knowledge of HTML. Instead, the last tutorials are focused on gathering data with Python from the web. In this case, you need to grasp to interact directly with HTML pages and you need some previous knowledge of it.

Web scraping is the process of collecting data from the web page and store it in a structured format, such as a CSV file. For example, if you want to predict the Amazon product review’s ratings, you could be interested in gathering information about that product on the official website.

You surely aren’t allowed to scrape data from all the websites. I recommend you first look at the robots.txt file to avoid legal implications. You only have to add ‘/robots.txt’ at the end of the URL to check the sections of the website allowed/not allowed.

As an example, I am going to parse a web page using two Python libraries, Requests and Beautiful Soup. The list of countries by greenhouse gas emissions will be extracted from Wikipedia as in the previous tutorials of the series.

Table of Content:
1) Import libraries
2) Create response object
3) Create a Beautiful Soup object
4) Explore HTML tree
5) Extract elements of the table

