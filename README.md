Check out the pdf file saved in this repository to view the project!

In this project, I perfrom the Upper Confidence Bound RL Algorithm to optimally pick one equity from each listed S&P 500 sector. Initialize a certain amount of money (initialized by parameter "start_money") into each sector. Then, on each trading day, the model will allocate all of its money in each sector to a single equity picked out by the UCB algorithm. While the money initialized to each sector at the beginning of the process is the same, it will not stay that way as each individual sector realizes varying returns. This dynamic distribution of funds to multiple sectors ensures portfolio diversification and risk mitigation, as multiple stocks across multiple sectors will always be invested in to reduce unsystematic risk, but the worse performing sectors have less money to invest. At the beginning of the next trading day, the position on each equity is sold, and the returns from each individual stock are reinvested in the stock picked by the algorithm for the next day.


The percent retuens of each sector are aggregated to demonstrate a total annualized return.


This specific backtest returns 14.4% annually, and is tested over the period of 2010-01-01 through 2019-12-31. It is one of many backtests conducted in this project by the club.
