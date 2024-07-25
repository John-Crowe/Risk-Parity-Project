# Risk Parity Portfolio

For this project, I am replicating the results from the 2012 paper, "Leverage Aversion and Risk Parity" by Asness, Frazzini, and Pedersen. This paper compares the stock portfolio, bond portfolio, value-weighted stock/bond portfolio, 60/40 portfolio, risk parity unlevered portfolio, risk parity portfolio, risk parity minus value-weighted portfolio and risk parity minus 60/40 portfolio. The output is from January 1929 to June 2010, at a monthly frequency.

Same as the Historical Market Return project, I imported the CRSP data for stocks and the risk free rate. I also use CRSP for the bond pricing as well. I combine the dlret and ret data for the stocks and encompass all returns in the final 'ret' column for stocks. In accordance with the French Fama methods, I use the 10 and 11 sharecodes and the 1, 2 and 3 exchanges. The URL containing details on this method is below:

https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html

# Relevant Libraries

* wrds
* pandas
* pandas-datareader
* numpy
* datetime
