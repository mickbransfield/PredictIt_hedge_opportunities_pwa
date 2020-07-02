# PredictIt_hedge_opportunities_pwa
### A web application that looks for hedge opportunities in user-inputted contracts.

There are opportunities for pairs tradiing in PredictIt markets due to inefficient pricing among various markets
and contracts. For example, if Trump winning is priced at $0.50/share and Biden winning is priced at $0.44/share,
the opportunity exists to buy an equal number of shares for both candidates and net a profit regardless of who wins.

### Please keep in mind:
* Users enter contract(s) numbers in 'Group A' and inversely correlated contract(s) in Group B. The application 
can't determine the relationship between contracts.
* While the code accounts for the 10% fee on gains from trades, it does not factor in the 5% withdrawl fee.
* While specific contract numbers need to be entered in the search page, the output will list any potential pairs
as 'Market: Contract: Yes/No'
