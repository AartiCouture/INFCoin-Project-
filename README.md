# INFCoin-Project

Inflation, by definition, is a general increase in prices and fall in the purchasing value of money. In the last year alone, inflation has risen by 7% according to the Consumer Price Index, or CPI.  

For our project, we created an ERC20 coin called INFCoin. INFCoin, or Inflation Coin, uses the percent change in CPI to adjust the amount of the holder's tokens. The tokens are added or subtracted monthly, depending on if inflation increases or decreases.

Our coin is a proof of concept as we still need to add an oracle to check inflation  programmatically instead of manually. 

For INFCoin, we created an ERC20 coin that includes a check inflation function.  The check inflation function checks for the percent change in inflation and then adds or subtracts the tokens based on the inflation rate to each token holder’s balance. This coin is a hedge against inflation. 

To demonstrate: 

First,  deployed the INFCoin sale.

<img width="1429" alt="INFCoin Deployer" src="https://user-images.githubusercontent.com/87285522/149602309-bd6daffd-556d-4e04-891a-e51aadb78f01.png">


Then, we deployed the contract for the crowdsale using the token sale address generated by the coin sale contract. 

<img width="1433" alt="INFCoin Crowdsale w:Token sale address" src="https://user-images.githubusercontent.com/87285522/149603764-3ef5531c-46f5-4fa2-a573-b951707bca65.png">

Following this, we 
