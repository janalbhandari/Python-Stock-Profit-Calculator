# Python-Stock-Profit-Calculator

The application is available at the following link: [Stock Profit Calculator](https://python-homework1.herokuapp.com)

This is a Python web application that it takes the following inputs:
- A stock symbol
- Allotment (number of shares)
- Final share price (in dollars)
- Sell commission (in dollars)
- Inital share price (in dollars)
- Buy commission (in dollars)
- Captial gain tax rate (in %)

And outputs the following items after computation:
- Proceeds (Allotment x Final share price)
- Cost (Allotment x Initial Share Price + commissions + Tax on Capital Gain)
- Net Profit (in dollars)
- Return on investment (in %)
- Break even price (in dollars)

## For example:

###### Compute Your Profit:

Ticker Symbol: 
ADBE

Allotment: 
100

Final Share Price: 
110

Sell Commission: 
15

Initial Share Price: 
25

Buy Commission: 
10

Capital Gain Tax Rate (%): 
15

###### PROFIT REPORT: 
Proceeds
$11,000.00

Cost
$3,796.25

Cost details: 
Total Purchase Price
100 × $25 = 2,500.00
Buy Commission = 10.00
Sell Commission = 15.00
Tax on Capital Gain = 15% of $8,475.00 = 1,271.25

Net Profit
$7,203.75

Return on Investment
189.76%

To break even, you should have a final share price of
$25.25
