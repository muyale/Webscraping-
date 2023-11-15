# Webscraping on the books to scrape website with python and beautiful soup
This is a project on webscraping on the books to scrape website.

Webscraping is essentially extracting information from a website and then converting the information into a form that 
a user can use . Webscraping can be quite useful in datascience .However not all websites allow webscraping and it is deemed illegal in some cases. Webscraping works by using a crawler and a a scraper.

Web scraping software accesses  the internet either through HTTP or a web browser, 
and the web crawler and web scraper work together to extract specific data from the web pages. There are many webscraping libraries for my case I used Beautiful soup library.
In webscraping,before data extraction takes place, the webcrawler must fetch the webpage. 
Fetching refers to the process of downloading a web page and content is then parsed,reformatted, or searched, with the extracted data then loaded into a database or copied into a spreadsheet.

First, the web scraper will be given one or more URLs to load before scraping. for my case it was the bookstoscrapewebsite
![Intro](https://github.com/muyale/Webscraping-/assets/111242297/c24ff7c7-d73d-40e8-bbcf-f04afaa4462c)

the website looks pretty much like this
![Books to scrape website](https://github.com/muyale/Webscraping-/assets/111242297/345908be-3804-4392-a166-945714f4d43a)

The webscraper loads the entire HTML code for the books to scrape website. 

Using my knowledge on css and html classes I obtained all the images ,titles  and ratings as shown below.
![css style](https://github.com/muyale/Webscraping-/assets/111242297/36908632-987b-4373-b671-918824420889)

Heres another example for another book.
![soumission](https://github.com/muyale/Webscraping-/assets/111242297/7135d69e-83ab-407d-b74a-a12da58df023)


I then went through the process of selecting the specific data I wanted from the page which was the name of the book,the price and rating.With this information I created a dataframe with
the use of the pandas dataframe.
![Final](https://github.com/muyale/Webscraping-/assets/111242297/b2ab38ef-366c-4bb3-8c83-49b68f0d78a5)

