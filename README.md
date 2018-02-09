# Financial stocks via marginal correlation graphs
In this project we want to study the dependency among financial stocks via marginal correlation graphs. 

We collect the daily closing prices for the stocks in the **S&P500** index between *January 1, 2003* through *January 1, 2008*, before the onset of the “financial crisis”.

The stocks are categorized into 10 Global Industry Classification Standard (gics) sectors, including:

+ Consumer Discretionary,
+ Energy, Financials, 
+ Consumer Staples, 
+ Telecommunications Services, 
+ Health Care, Industrials, 
+ Information Technology, 
+ Materials
+ Utilities. 

So selecting a sensible portfolio of this stocks and choosing two different association measures:

* Pearson 
* Kendall

we implement the Bootstrap procedure to build up our marginal correlation graphs.

The results demonstrate that stocks from the same gics sectors tend to be clustered together.

![](/Users/alfonsodamelio/Desktop/financial.png =100x20)
