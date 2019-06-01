# HIVE-Assignments

Assignment01
-------------------------------------------------------------------------
Data Set: The NBER U.S. Patent Data

Data Link: http://www.nber.org/patents/

We will use the following data sets:

        Patent data, including constructed variables:

        Data link: http://www.nber.org/patents/apat63_99.zip

        Summary of this data is given here - http://www.nber.org/patents/pat63_99.txt

Problems 
1. Create an internal table for Patent data set.
   (Make sure not to include the header row)
2. Create an external table with dynamic partitioning for Patent data set so that it can be used efficiently for queries which require looking into patents granted for given year.
   (Use data from previous table and partition by Grant Year)
3. Find out number of patents granted in year 1963.
4. Find out number of patents granted in each country in year 1999.

*Submit text/docx file with hive statements



Assignment02
--------------------------------------------------------------------------------------
Data Sets: NASDAQ Exchange Daily 1970-2010 Open, Close, High, Low and Volume

Download links:    NASDAQ_dividends_A.csv     NASDAQ_daily_prices_A_sample.csv

Summary of data: There are two types of data

1.File name starting with NASDAQ_daily_prices*: This file is a CSV (comma seperated values) file which contains following fields which are self explanatory.

exchange,stock_symbol,date,stock_price_open,stock_price_high,stock_price_low,stock_price_close,stock_volume,stock_price_adj_close


2.File name starting with NASDAQ_dividends*: This file is a CSV (comma seperated values) file which contains following fields which are self explanatory.

exchange,stock_symbol,date,dividends

Find the Solution for following problems
1. Create an external table for NASDAQ daily prices data set.

2. Create an external table for NASDAQ dividends data set.

3. Find out total volume sale for each stock symbol which has closing price more than $5.

4. Find out highest price in the history for each stock symbol.

5. Find out highesh dividends given for each stock symbol in entire history.

6. Find out highest price and highesh dividends for each stock symbol if highest price and highest dividends exist.
