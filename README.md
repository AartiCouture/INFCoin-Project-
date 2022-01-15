# INFCoin-Project

Inflation, by definition, is a general increase in prices and fall in the purchasing value of money. In the last year alone, inflation has risen by 7% according to the Consumer Price Index, or CPI.  

For our project, we created an ERC20 coin called INFCoin. INFCoin, or Inflation Coin, uses the percent change in CPI to adjust the amount of the holder's tokens. The tokens are added or subtracted monthly, depending on if inflation increases or decreases.

Our coin is a proof of concept as we still need to add an oracle to check inflation  programmatically instead of manually. 

For INFCoin, we created an ERC20 coin that includes a check inflation function.  The check inflation function checks for the percent change in inflation and then adds or subtracts the tokens based on the inflation rate to each token holder’s balance. This coin is a hedge against inflation. 

To demonstrate: 
<img width="1440" alt="INFCoin Deployer" src="https://user-images.githubusercontent.com/87285522/149601961-169df39e-2d18-4643-96d1-26e2453e321e.png">

