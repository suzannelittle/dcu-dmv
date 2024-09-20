## Introduction to scraping data from websites

Recall that when I talked about possible sources of data one of the options was to scrape data from websites. Here we look at some of the pros and cons of doing this, general rules that you should bear in mind and some general tips on implementing a scraping script.

<a id="h.wbshpez88cdt" name="h.wbshpez88cdt"></a>

### What is scraping?

Websites don’t always provide their data for easy download or via an API as CSV or JSON. Or even as neat and tidy tables where you can try the pandas function [read\_clipboard\(\)](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_clipboard.html) to copy and paste tabular data\!

Sometimes you need to get dynamic data from a website but there’s no API. If you know a little bit about how HTML works then you can use _scraping_ to gather the raw data. Downloading and processing the HTML files is how search engines index the Internet. 

   &nbsp;&nbsp;&nbsp;**Scrape:** to extract data from semi\-structured sources \(e.g., webpages\).

   &nbsp;&nbsp;&nbsp;

   &nbsp;&nbsp;&nbsp;**Crawling:** traversing the web via links in \<a\> tags to gather data via scraping.

   &nbsp;&nbsp;&nbsp;

The general process is as follows:

<!---->
1. Have a plan \(how to identify the data items on the page\)

2. Request webpage \(e.g., urlopen, requests\)

3. Parse HTML \(e.g., lxml, beautifulsoup\)

4. Store data \(e.g., as list or dict\)

5. Format as required \(e.g., CSV, json, dataframe, sql\)

You will almost certainly need to clean the data as scraping can be very prone to introducing errors and artefacts. 

<a id="h.iydm02hcbnzs" name="h.iydm02hcbnzs"></a>

### Good practise for scraping

Some good rules to remember about scraping \(from [Gregreda.com](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/)\):

<!---->
1. You should check a site's terms and conditions before you scrape them. It's their data and they likely have some rules to govern it.

2. Be nice\! A computer will send web requests much quicker than a user can. Make sure you space out your requests a bit so that you don't hammer the site's server and cause a denial of service attack.

3. Scrapers break: sites change their layout all the time. If that happens, be prepared to rewrite your code.

4. Web pages are inconsistent: there's sometimes some manual clean up that has to happen even after you've gotten your data.

Python provides some handy libraries to help with scraping including: 

<!---->
- requests \- downloading the page

- BeautifulSoup \- parsing the HTML into an object to search and manipulate

   &nbsp;&nbsp;&nbsp;

These libraries are fine for once off tasks or exploring scraping but for more stable, longer term projects check out [Scrapy](https://doc.scrapy.org/en/latest/intro/tutorial.html ). There are other tools for web scraping given in this [ranked list](http://www.aioptify.com/top-web-scraping-frameworks-and-librares.php). 

**Consider:**&nbsp;Have you ever needed to get data from a website? How did you do it and did anything go wrong? If you haven’t then can you think of when a web scraper might be useful?

<a id="h.w6v99l4q0w3h" name="h.w6v99l4q0w3h"></a>

### Exercise

Here we try some simple web scraping to get a list of book titles and prices from an online store \- [http://books.toscrape.com/](http://books.toscrape.com/). This is a fake book store created to provide a demo web site to practise scraping. 

View the [Colab notebook](https://github.com/suzannelittle/ca682i/blob/master/notebooks/2_4_8_Web_Scraping.ipynb) hosted on Github to see the code. Can you alter it to include the star rating for each book?

   &nbsp;&nbsp;&nbsp;Open the notebook in Colab and don’t forget to save the notebook to your own Google Colab account to save your work.

<a id="h.jby0m61f6cbh" name="h.jby0m61f6cbh"></a>

**A challenge for you**: Can you get a list of all the All Ireland Senior Football Champions \(just the county name\) from </span><a id="h.jby0m61f6cbh" name="h.jby0m61f6cbh"></a> [https://en.wikipedia.org/wiki/List\_of\_All\-Ireland\_Senior\_Football\_Championship\_finals](https://en.wikipedia.org/wiki/List_of_All-Ireland_Senior_Football_Championship_finals)

### <span style="font-size:11pt;">Remember: don’t hammer wikipedia by repeatedly using requests to get the page\! Get it once and then work out your scraping code. </span>

<a id="h.28ryejl9zijl" name="h.28ryejl9zijl"></a>

### Resources

Some extra tutorials and guides if you are interested in learning more.

<!---->
- [Beautiful Soup: Build a Web Scraper With Python – Real Python](https://realpython.com/beautiful-soup-web-scraper-python/)
- [Web Scraping 101 with Python](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/)

<!--
<style>
th {
  font-weight: normal;
}
td {
  border: 2px solid black;
}
ol ol { 
  list-style-type: lower-alpha; 
}
ol ol ol { 
  list-style-type: lower-roman; 
}
img {
  max-width: 100%;
  height: auto;
  object-fit: contain;
}
</style>
-->
