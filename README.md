# Chapter 3 Challenge

# we are considering arbitrage opportunities in Bitcoin and other cryptocurrencies. As Bitcoin trades on markets across the globe, we you capitalize on simultaneous price dislocations in those markets by using the powers of Pandas. 
# For this assignment, you’ll sort through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. Your task is to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.
# This aspect of the Challenge will consist of 3 phases.
# Collect the data. Using the Pandas read_csv function and the Path module, import the data from bitstamp.csv file, and create a DataFrame called bitstamp. Set the DatetimeIndex as the Timestamp column, and be sure to parse and format the dates.
##Read in the CSV file called "bitstamp.csv" using the Path module. 
## The CSV file is located in the Resources folder.
## Set the index to the column "Date"
## Set the parse_dates and infer_datetime_format parameters
## Use the head (and/or tail) function to confirm that the data was imported properly.
## repeating same steps in this section to collect coinbase data. 

# Prepare the data.
## To prepare and clean your data for analysis, complete the following steps:
## For the bitstamp DataFrame, replace or drop all NaN, or missing, values in the DataFrame.
## Use the str.replace function to remove the dollar signs ($) from the values in the Close column.
## Convert the data type of the Close column to a float.
## Review the data for duplicated values, and drop them if necessary.
## Repeat Steps 1–4 for the coinbase DataFrame.
# Analyze the data.
## Your analysis consists of the following tasks:
## Choose the columns of data on which to focus your analysis.
## Get the summary statistics and plot the data.
## Focus your analysis on specific dates.

Calculate the arbitrage profits.

Step 1: Choose columns of data on which to focus your analysis.
Select the data you want to analyze. Use loc or iloc to select the following columns of data for both the bitstamp and coinbase DataFrames:

Timestamp (index)

Close
# Read in the CSV file called "bitstamp.csv" using the Path module. 
# The CSV file is located in the Resources folder.
# Set the index to the column "Date"
# Set the parse_dates and infer_datetime_format parameters
