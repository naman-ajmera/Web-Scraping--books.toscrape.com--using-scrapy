# Web Scraping  books.toscrape.com  using scrapy
This is a Web Scraping project using scrapy framework. 
It scrapes the above website for 1.Title 2.Price 3.Image Url 4.rating 5.description 6.upc 7.Product type 8.Availibility etc on all the webpages by going on the next url 
TO RUN:- scrapy crawl books
This spiders has also a Scrapy Argument Function
TO RUN with category such as Childrens :- scrapy crawl books -a category="http://books.toscrape.com/catalogue/category/books/childrens_11/index.html"
This spider also has a Close Function which Creates a file with results by renaming the latest .csv file with the name "foobar.csv"
TO RUN:- scrapy crawl books -o items.csv
