The dataset given here is a NYSE stock data for the year 2009 which is ordered according to date for each stock. However there are entries of data inbetweeen which contain details of stock for other years (which can be removed during analysis).The first initial rows are the data of a stock for whole year, and is fallowed in same fashion for each stock.

The data is analysed using one of the scripting language called PIG.
The codes for analysing the data is also provided.
The objective of the study was to analyze the stock trade data to find the maximum and minimum traded stock on a day for a given week. 

The analysis done requires chaging the dates (in code: z = filter data by date == '2009-12-31' or date == '2009-12-30' or date == '2009-12-29' or date == '2009-12-28' or date == '2009-12-24' or date == '2009-12-23' or date == '2009-12-22';) to get the maximum and minimum traded stock data, and the other lines of code statys same for processing. Because of the inconvenience created due to network issue the complete output was not able to be uploaded. 

Hope my efforts are acceptable.

I expect someone to suggest me with a code to:

- generate output in a tabulated manner 
- also without the need to write and execute each single line of similar code to get the output for whole dataset 
(hint: may be there is need to make use of loops) 
