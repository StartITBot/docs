
# Stock-market – place for investing money

The Stock Market is a virtual marketplace where users can trade stocks of various companies using the bot's virtual
currency. It simulates the real-world stock market and allows users to experience the thrill of investing and trading
stocks without any real financial risk.

Here is a list of commands that you can use within the Stock Market:

- `/stockmarket backpack [user]`: Displays the stocks you currently own in your backpack.
- `/stockmarket info <name>`: Provides detailed information about a specific stock.
- `/stockmarket sell <quantity> <name>`: Allows you to sell a specific quantity of a stock.
- `/stockmarket sell-all`: Sells all the stocks you currently own.
- `/stockmarket buy <quantity> <name>`: Enables you to buy a specific quantity of a stock.
- `/stockmarket list`: Lists all available stocks for trading.

## /stockmarket info Command

You can use the `/stockmarket info <name>` command to retrieve detailed information about a specific stock. The `<name>`
parameter refers to the symbol of the stock you want to know more about. The information provided includes the
stock's name, symbol, current price, market cap, trading volume, and price change percentage.

We are trying to be as accurate as possible. To archive that we are constantly connected to our 3rd party provider that
sends us live stock data. However, we are not responsible for any inaccuracies. Please don't invest real money based on
our bot :c

## /stockmarket buy Command

To buy stocks, you can use the `/stockmarket buy <quantity> <name>` command. Specify the `<quantity>` parameter to
indicate the number of stocks you want to purchase, and provide the `<name>` parameter as the symbol of the
stock you wish to buy. The bot will add the corresponding stocks to your backpack.

## /stockmarket sell Command

When you want to sell stocks, use the `/stockmarket sell <quantity> <name>` command. Specify the `<quantity>` parameter
to indicate the number of stocks you want to sell, and provide the `<name>` parameter as the symbol of the stock
you wish to sell. The bot will remove the specified quantity of stocks from your backpack and credit the virtual
currency equivalent to your balance.

## /stockmarket list Command

You can view all available stocks for trading using the `/stockmarket list` command. The bot will display a list of
stocks, including their names, symbols, and current prices. This information helps you make informed decisions when
choosing stocks to invest in.

We are supporting the following stocks:

- [Most popular cryptocurrencies](https://www.tradingview.com/markets/cryptocurrencies/prices-all/)
- US Stock
  Market: [AMEX, NASDAQ, NYSE stock exchanges](https://www.tradingview.com/markets/stocks-usa/market-movers-all-stocks/)

View full list on supported cryptocurrencies and stocks on [www.startit.bot/stocks](https://startit.bot/stocks).

## /stockmarket backpack Command

To check the stocks you currently own, use the `/stockmarket backpack [user]` command. If you provide the `[user]`
parameter, it will display the backpack of the specified user. Otherwise, it will show your own backpack. The backpack
displays the stocks you own, along with quantities.

## /stockmarket sell-all Command

If you want to sell all the stocks you own, simply use the `/stockmarket sell-all` command. The bot will remove all
stocks from your backpack and credit the virtual currency equivalent to your balance.

## Admin: Configuring the Stock Market

To start playing around with stock market on your server go to the dashboard and set conversion rate between your
virtual currency and dollars.

![](../assets/v8.png)

Conversion rate `US$1 - 4` means that 1 real dollar is worth 4 virtual currency units. For example if you want to buy a
stock of Apple Inc. witch costs 150 real dollars you need to spent **600 virtual currency**.
