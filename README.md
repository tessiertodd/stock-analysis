# Stock-Analysis Overview

## Overview of Project: ##
Help our client (Steve) to analyze stock performance of a number of investments for which he has provided data. 


## Purpose: ##
Steve needs some help sorting through all the data on stocks he has to help identify particular stocks that would be good for his parents portfolio as he is looking to provide them with some investment recommendations.


## Results: ##

### Stock Performance between 2017 and 2018 ###
![Table_2017_2018_Returns](https://github.com/tessiertodd/stock-analysis/blob/main/2017%20and%202018%20Returns.png)

The stock performance overall in 2017 was much more positive than in 2018.  In 2017 only one stock TERP had negative returns (-7.2%) while all other stocks had returns between +8.9% and +199.4%.  In 2018 there were only 2 stocks with positive returns (ENPH and RUN), however their returns in 2018 were lower than in 2017.

Daily volumes in 2018 versus 2017 were up overall +4.4%, however that differed between stocks with 7 of 12 stocks daily volume up while 5 were down.  ENPH and RUN both had a large increase in daily traded volumes in 2018, only one stock DQ had daily volume increase more, but return was negative -62.6% for DQ in 2018.

Its tough to pick stocks with only 2 years of data, and with not having additional information of factors that may impact the stock performance in the future.  However, even with our limited information, given the performance of ENPH and RUN over the 2 years, I would recommend Steve take a closer look at these stocks as potential investments for his parents.

### Execution Time Comparison Between Original Green Stocks and Refactored VBA Challenge ###

#### Original Green Stock Code ####
![Table_2017_GreenStock](https://github.com/tessiertodd/stock-analysis/blob/main/Green_Stocks_2017.png)         ![Table_2018_GreenStocks](https://github.com/tessiertodd/stock-analysis/blob/main/Green_Stocks_2018.png)

#### Refactored VBA Challenge Code ####
![Table_2018_VBAChallenge](https://github.com/tessiertodd/stock-analysis/blob/main/VBA_Challenge_2017.png)      ![Table_2018_VBAChallenge](https://github.com/tessiertodd/stock-analysis/blob/main/VBA_Challenge_2018.png)

The refactored VBA Challenge code runs much faster than the original Green Stock code... over 5x faster for both 2017 and 2018.  Interesting to note than times between 2017 and 2018 for both the original and refactored code ran slightly faster for 2017 than 2018... not sure there is a reason for that since both years had the same # of rows of data that had to be processed... could be a random outcome.

### Summary ###

#### Advantages and Disadvantages of Refactoring Code ####

ADVANTAGES
•	Able to take some good code and make it better and/or more efficient - more efficient (processing time) is important when looking to process large datasets.
•	Opportunity to reduce the complexity of the code - making it more readable for others or yourself at a later date.

DISADVANTAGES
•	Time consuming process - you may not know how long it will take to complete.
•	Could introduce errors or bugs that were not in the original code.


#### Advantages and Disadvantages of Original and Refactored VBA Script ####

ADVANTAGES
•	Refactored VBA runs quicker than original (however both run in under a second so not much of an advantage with the limited data we had).
•	Original code was a little less complex given ticker was only array being used.

DISADVANTAGES
•	Original takes more time to run than refactored VBA.
•	Original code had to be run in two-steps - formatting setup as a seperate sub.
•	Refactored code had some additional complexities - like multiple arrays for the various variables.
