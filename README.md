# Expedia-Twitter-Page-Scrapper  

The script [expedia-twitter-scrapper](https://github.com/sushantgupta1206/GUPSUS01/blob/master/ExpediaTwitterScrapper/ExpediaTwitterScrapper/spiders/expedia_twitter_scrapper.py) is a python script to be run from a command line and it will scrape Expedia's Twitter feed into a html page is then parsed to re- write the 8 most recent tweets into a text file which uses JSON [Top_8_tweets](https://github.com/sushantgupta1206/GUPSUS01/blob/master/ExpediaTwitterScrapper/Top_8_Tweets.json).  

**Technology Stack used :**   
> Python 2.7  
> Scrapy Library in python  
> Beautifulsoup Library   

## The Output and inferences :   
  
My main objective while solving the question was not just reporting the tweets but also **analyse some data related to the tweets.**  
These are the following questions that can be answered using the reactions people post on the tweets:    
> 1. How many people re-tweet on the tweet?  
> 2. How many people mark the tweet as a 'favorite/ like'?  
  
Please check the output [file](https://github.com/sushantgupta1206/GUPSUS01/blob/master/ExpediaTwitterScrapper/Top_8_Tweets.json) here. It contains json objects listed in the original form. The file will be auto-generated when we run the code.   
The below is an edited version of the sample output I get after running the code: 
![image]()
  
**Steps to Run the code:**   
> 1. clone the repository using `git clone https://github.com/sushantgupta1206/GUPSUS01.git` on the local machine  
> 2. Navigate to the folder `\GUPSUS01\ExpediaTwitterScrapper`  
> 3. install dependencies using `pip install bs4` for beautiful soup; `pip install Scrapy` for installing Scrapy  
> 4. navigate the the '\GUPSUS01\ExpediaTwitterScrapper' folder and then run the spider by using `scrapy crawl expedia_spider` where expedia_spider is the name of the spider I use to scrape the Twitter feed of Expedia.  
> 5. Please check the 'Top_8_tweets.json' file to verify the output. 

**Further Analysis/ Edits:**   
1. Get the total number of followers for the Expedia's twitter feed and find the number of people who re-tweet and like the tweets. 
This is give Expedia an estimation of what percentage of people are active users and actually follow the tweets.
2. Modify the JSON data to any desired form for reading or transfering pursposes. 

**References and Readings**
> 1. https://www.crummy.com/software/BeautifulSoup/bs4/doc/
> 2. https://minimaxir.com/2015/07/facebook-scraper/
> 3. https://doc.scrapy.org/en/latest/topics/spiders.html#topics-spiders



