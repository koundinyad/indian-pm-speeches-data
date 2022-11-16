# Indian Prime Minister Speeches Data

Includes

1. All published speeches by Manmohan Singh (2004-14)
2. All published speeches by Narendra Modi (2014-2022)

Data scraped with `BeautifulSoup` and `Selenium` from

1. https://archivepmo.nic.in/drmanmohansingh/all-speeches.php
2. https://www.pmindia.gov.in/en/tag/pmspeech/


`.data` JSON
```
[{
	date: ,
	url: ,
	title: ,
	location: ,
	lang: ,
	original_text: ,
},...]
```
Note: No `location` value for Narendra Modi speeches data

--- 
Scraper notebook to be published