---
layout: post
title:  "Simple web crawler using python"
date:   2018-09-16
desc: "Simple web crawler using python"
keywords: "web crawler,python"
categories: [Python]
tags: [crawler]
icon: icon-html

---
# Simple Web Crawler
The most straightforward crawler that will crawl a site by bringing all the URL's for a particular given website

  - The crawler does not follow external websites
  - Output can be stored in external file using standard output redirection operator ">"
 
### Tech
This web-crawler built using Python2.7 & uses a number of different python libraries:
* BeautifulSoup
* urllib
* This crawler also runs using version python2.7+

### Build & run
```sh
1. Copy spider.py on your machine
2. Make file execulable using 'chmod +x spider.py'
3. run the file using : '$ python cr.py >> result.txt'
```
### Given more time, what could be done with crawler? 
* Track the content changes
* Create datasets for machine learning ex. malacious/benign url dataset
* Create chatbots to identify if url is malacious or benign or can create web plugins to block particular url's
* To create search engines etc. 

### Code & result  
```sh
1. Web crawler : https://github.com/AbhishekShaha/web-crawler-python/blob/master/spider.py
2. Result file : https://github.com/AbhishekShaha/web-crawler-python/blob/master/result.txt
```
