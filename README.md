# Changing-Room-Coding-Challenge
## Description
For this coding challenge, I was asked to create a web crawling application using Python. I used BeautifulSoup as my main library to crawl the website www.fordays.com. Since I was tasked to crawl not the entire website but a few products, I cralwed the products and their attributes of the womens' tops section. In this file, I will explain every step I took to complete the coding challenge and my strategy towards how to scrape the entire website as well as making automatic updates after storing in Postgresql database. 
## Python File
### Coding Part
Before starting the coding part, I examined the clothing website www.fordays.com and found out that all products can be categorized into four categories: men's, women's, baby and kid's and uncategorized. After importing necessary modules, I tested the status and retrieved the test url which is every product in the women's top category. Then, using a for loop, I retrieved the urls of each specific product in the category.
For the web scraping parts, I wrote down comments that details the uses and logic of my code in the Python file and finally I outputted the results of the web scraping. 
### Strategy of Scraping Entire Website
In this part of the Python file, I explained my strategy of scraping every product's information on the website. 
