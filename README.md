# Currency-Strategy
Scoring Mechanism for picking best and worst currencies, Carry trade implementation

*Picking Portfolio by Currency Scoring*

Scoring Mechanism for the Currency Set consisting of 18 currencies wrt to USD.

Data set from Jan 2010.
Periodicity of Rebalance : 3 Months (Quarter)

Factors Used:
1) Current Account as percentage of GDP
2) Real Interest Rate
3) Real Effective Exchange Rate

Picking Best currency from score created -> Long them for the Quarter

Picking Worst currency from score created -> Short them for the Quarter

Limitations and Improvements:
1) For now the current account data we have is for a quarter, the rebalancing frequency can be changed to every month if monthly current account data is available.
2) Other factors can be added ( Long term debt, Inflation rate, etc)

