# Python-WebCrawler

This is a web crawler written in Python. You will have to install BeautifulSoup before you can use it.


### Install BeautifulSoup

The steps are given below: 

1) Go to this site: http://pypi.python.org/pypi/beautifulsoup4 

2) Download the file "beautifulsoup4-4.1.3.tar.gz" 

3) Unpack the file into a comfortable location 

4) Open terminal and go to the unpacked folder 

5) Execute the following commands: 

	python setup.py build 

	python setup.py install 

6) If the install is successful, you will not see any errors on the terminal. 


### Running the crawler

Download the crawler.py file from the repo. This file is used to crawl a given site. I have listed a few use cases below:

The following command will display the total number of links found on a particular website after crawling:
	
	python crawler.py http://website.com

If you want to crawl only upto a particular depth, then:
	
	python crawler.py -d 2 http://website.com

If you want the links which are only found on this particular url:
	
	python crawler.py -l http://website.com

There are many other options you can explore. Execute the following in the terminal and you will see a bunch of options:
	
	python crawler.py --help

