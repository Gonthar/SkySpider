# SkySpider

## A collaborative project for airline connections scraping
Temporarily scraping famous people quotes :smirk:

Example use: `scrapy crawl quotes`
For file output: `scrapy crawl quotes -o quotes.json`

## Development plan
* Add a database for item storage
* Ensure uniqueness of entries, remove duplicates
* Develop a flight item
* Make a list of flight/airline related sites to scrape
* Develop first flight spider
* Add Selenium to the project to deal with dynamic websites
* Integrate proxy networks (ProxyMesh?) to avoid getting banned
* Create documentation, especially focused on new spider creation, Selenium, and xpath/css selection
* Develop other flight spiders
* Decide between web or desktop-based GUI and tech (Django, PyQt5?)
* Develop simple GUI
* Setup scheduled scraping (ScrapydWeb?)