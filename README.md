# EquityPortfolio

The jupiter notebook contains R code for Equity Portfolio for data of 10 stocks for year 2018. 
1. IBM
2. Microsoft
3. Google
4. Apple
5. Amazon
6. Facebook
7. Netflix
8. Tesla
9. Oracle
10. SAP

The portfolio is started with $5 million to invest. 5 first stocks in the list above are purchased by splitting the money in 5 equal parts(ie %1 million) in 2 Jan 2018. As you can purchase stocks only in whole number, the money left out is kept in zero interest saving account.
The program use the strategy of "5 days rebalancing of buying low" ie sell all the stocks on the 5th business day, add money to the saving account and immediately split the money again in 5 equal parts to buy the stocks dropped most(in terms percetage).
It continues for the whole year and feature of stock divident is also added which adds to the cash if stock is sold on divident day.
The program displays the portfolio after every 5 business days.
After the end of year it delivers the MTM. Using all the data optimal days interval that maximizes the MTM(Market To Market value) is calculated.

With that the strategy of "5 days rebalancing of buying high" is used to buy the stocks. 
Both the strategies are compared. Also program add high tech index curves in the notebook.
