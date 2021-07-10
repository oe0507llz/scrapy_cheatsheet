# scrapy_cheatsheet

### Scrapy Tutorial
https://docs.scrapy.org/en/latest/intro/tutorial.html

### Logging in with Scrapy FormRequest
https://python.gotrained.com/scrapy-formrequest-logging-in/

### Send Post Request in Scrapy
https://stackoverflow.com/questions/30342243/send-post-request-in-scrapy
```
frmdata = {"id": "com.supercell.boombeach", "reviewType": '0', "reviewSortOrder": '0', "pageNum":'0'}
url = "https://play.google.com/store/getreviews"
yield FormRequest(url, callback=self.parse, formdata=frmdata)
```

### Crawling with Scrapy – Exporting Json and CSV
http://scrapingauthority.com/2016/09/19/scrapy-exporting-json-and-csv/

### Scraping Web Pages with Scrapy
https://www.youtube.com/watch?v=1EFnX1UkXVU
<br>A nice demo how to scrape data from craigslist. 

### Scraping the Web with Scrapy
https://www.youtube.com/watch?v=eD8XVXLlUTE

### Using Scrapy on reddit.com
https://www.youtube.com/watch?v=nnnDshuflSI
<br>One take-away is that we can edit the setting for logging; another take-away is that we can download pdf and spreadsheet. 

### IMDB spider 
https://github.com/alexwhb/IMDBspider

#### 4 Ways to Debug Scrapy (Including Logging)
https://www.youtube.com/watch?v=5YmyALotdn0


