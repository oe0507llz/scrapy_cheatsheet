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
