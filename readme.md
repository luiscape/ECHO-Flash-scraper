ECHO Flash Scraper 
==================

The idea is to scrape data out of ECHO's Flash daily briefs (http://ec.europa.eu/echo/news/echo-flash/2013/20131009_en.htm) and export them into a data.frame (and CSV file). The final output would be to comine these qualitative attention into some sort of an `attention-index` that could be used to measure and compare the attention humanitarian organizations give to certain crisis around the world. 

The RSS feed could be parsed instead: http://ec.europa.eu/echo/rss/echo-flash.xml


Resources
---------

	--> Writen in `Python3`. 
	--> Using `urllib2`
	--> Using `BeautifulSoup4`