# StockTest
1. There are 6 classes in addition to the main class(GBCExchange).
2. Stock and initStock classes help to build the stock.

3. Trade and TradeHelper classes help in building the trade.

4. FormulaHelper class implements all the functions required.

5. Stock class creates the stock template using builder pattern and InitStock class initialises 
   the stock with the data given in the simple stocks exercise as a stock Array List.

6. Trade class creates a Trade template with stock as an attribute and adds other trade details to that template. 

7. Using TradeHelper class 10 entries for buying and selling trades have been done with arbitrary values. Some bought and some sold.

8. One of the trade "JOE" has been deliberately kept as a transaction that has been done 15 mn before the average stock price is calculated and the rest of the 4 trades are made within 15mn time frame so that the avg stock price can be calculated on those 4 stocks.

9. It has been assumed that Ticker Price of the stock is Last Dividend + Par VAlue of a stock and the calculations are done 
    based on this assumption.
