# Analysis of Different Types of Communication
In this project, we will explore the fundamental differences between the language used in:
1. Speeches
2. Songs
3. Potentially more to come (poems, essays)

#### Important Packages Used
* NLTK 
* pandas
* scikit-learn
* selenium
* Beautiful Soup 4
* TextBlob
* re (part of Python's standard library, but still important)

## Sample Selection
A number of speeches and albums worth of song lyrics will be analyzed. Current max is around 30 each due to the selection being scraped.
Popularity itself is difficult to quantify, so I based the choice of albums based on most sold and speeches based on what was available.

Methodology for sample selection is very important. You want to ensure selection processes have as little bias as possible, but this is a for fun project, so I hope you'll excuse me for picking speeches based on what is on James Clear's website, which is listed in alphabetical order based on the orator's last name.

Please do not ignore selection methodology (as seen here) if doing a project where the results matter.

## Data Collection
Web scraping will be conducted using both Selenium and Beautiful Soup (so I can learn about using both). 
Details on when one is a better alternative is detailed in the preprocessing notebooks, as well as some notes on how to be a good website patron when scraping. You don't want to slow/crash their site, get banned or worse.

Speeches transcripts from:
https://jamesclear.com/great-speeches/

Album Selection based off of:
https://www.businessinsider.com/50-best-selling-albums-all-time-2016-9

Songs lyrics from:
https://www.azlyrics.com/
