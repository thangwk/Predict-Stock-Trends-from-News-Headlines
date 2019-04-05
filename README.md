# Predict-Stock-Trends-from-News-Headlines
This is the code for the project from Datacamp on the topic of "Predict Stock Trends from News Headline" by Josiah Thang
Solution codes for the project. Enjoy!


1. Searching for gold inside HTML files
It used to take days for financial news to spread via radio, newspapers, and word of mouth. Now, in the age of the internet, it takes seconds. Did you know news articles are automatically being generated from figures and earnings call streams? Hedge funds and independent traders are using data science to process this wealth of information in the quest for profit.

In this notebook, we will generate investing insight by applying sentiment analysis on financial news headlines from FINVIZ.com. Using this natural language processing technique, we can understand the emotion behind the headlines and predict whether the market feels good or bad about a stock. It would then be possible to make educated guesses on how certain stocks will perform and trade accordingly. (And hopefully, make money!)

Facebook headlines from FINVIZ.com

Why headlines? And why from FINVIZ?

Headlines, which have similar length, are easier to parse and group than full articles, which vary in length.
FINVIZ has a list of trusted websites, and headlines from these sites tend to be more consistent in their jargon than those from independent bloggers. Consistent textual patterns will improve the sentiment analysis.
As web scraping requires data science ethics (sending a lot of traffic to a FINVIZ's servers isn't very nice), the HTML files for Facebook and Tesla at various points in time have been downloaded. Let's import these files into memory.

Disclaimer: Investing in the stock market involves risk and can lead to monetary loss. The content in this notebook is not to be taken as financial advice.
