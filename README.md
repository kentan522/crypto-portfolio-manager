# crypto-portfolio-manager
Spreadsheet portfolio manager with live crypto prices with VBA code implementation for ease of management.

Crypto coin prices are pulled from CoinGecko.

## Guide to using the spreadsheet

### Filling in the required columns (yellow headers)

1. Fill in your coin's handle under the Coin column (only top 300 cryptocurrencies (in market cap) data are pulled from CoinGecko). 

	- Do not leave rows of blanks. Fill in coins from the top row downwards
	
2. Fill in the USDT available table in cell K4 (USDT represents the stablecoin for crypto trades)

4. Fill in the Holdings column (column D) based on number of coins you own

6. Fill in the Avg. Price column (column E) based on average price of purchase of coins

	- If more coins are purchased/sold, please utilise the edit holdings table on the right (average price will be automatically updated)
	
	- When a purchase is made, USDT will be deducted; when a sell is made, USDT will increase 

### Updating Portfolio

Press the "Update" button to update all cryptocurrency market prices and  overall portfolio status

### Buying and Selling Owned Coins

1. Utilise the table "Buy and Sell Current Coins". When a purchase is made, USDT will be deducted; when a sell is made, USDT will increase. The average price of 

your coins will be automatically updated.

2. For buying new coins, please fill in the required yellow columns from scratch.

3. Do note that to undo a buy or a sell, you have to click the corresponding "Undo Buy" or "Undo Sell" button.

### Adding Portfolios

- Feel free to clone the sheet to add another portfolio (eg. hodl portfolio, trading portfolio etc.)

### Deleting Coins

- Deleting coins has to be done manually. Select the row corresponding to the coin and delete. If coins to be deleted lies in a middle row, just delete holdings. 

### Caution and Additional Comments

- Spreadsheet is done on version 2019 of MS Excel. Not too sure if it's compatible with all Excel versions.

- Sometimes the web query to CoinGecko may not work, just try again after a few hours. 

- Do not fill up coins in rows where theres no filled row above it. The code will not be able to read that row.

- Do make a copy of the sheet if you wish to manage multiple portfolios

### Closing 

Feel free to reach out if there are any issues with the spreadsheet. Apologies if the code was done rather crudely, the crypto space is constantly rolling 24/7, 
which leaves me no time for efficient coding at the moment!



