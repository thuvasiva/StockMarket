**Stock Market Simulator**

A Java Abstract Window Toolkit (AWT) application which simulates a stock market. The user of the application may purchase or sell a set of Financial Instruments within the limits of the their personal cash balance. The Financial Instruments are Stocks, Shorts, Bonds and Cash. The instruments all fluctuate in value over time according to predefined algorithm for each type of instrument. Once the user quits the simulation, their final balance is outputted into a text file.
The simulation moves day by day when the user explicitly decides to move on to the next day, upon which new values for each of the instruments are calculated.
Shorts are special Stocks which by purchasing gives the user cash (ie negative purchase), which the user has to pay back upon the expiration of the Short's term.
Bonds are a secure type of instrument which will always increase in value over time but are more predicatable (cannot expect large increases in value as for Stocks).

Additional Features: 
New instruments may be generated manually by the user on demand.
Various instruments may be removed automatically as long as the user does not own them.
Events of variant significance can happen over time which cause the inflation rate of the whole market to change (and affect the value of instruments).
Moving averages for each of the instruments can be calculated, which can be used to indicate trends in the price of each instrument (increasing/decreasing/stable in price).

Screenshot of application when first started:
![image](https://github.com/user-attachments/assets/d99f9fb3-7bd9-474a-8bab-ee1841694519)

