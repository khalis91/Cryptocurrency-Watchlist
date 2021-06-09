# Cryptocurrency-Watchlist

Try it out https://t.me/tofucryptowatchlist_bot or @tofucryptowatchlist_bot on telegram!!

![alt text](https://github.com/khalis91/Cryptocurrency-Watchlist/blob/main/TofuCryptoTelegram.jpg?raw=true)


How to create Telegram Bot?

Step 1: Launch BotFather on Telegram
Search for @botfather on Telegram and launch the bot. BotFather is a bot that helps us create and manage Telegram bot interfaces.

Step 2: Create a Telegram bot interface
Use the /newbot command to trigger BotFather which will ask you for the details of the bot you want to create.
BotFather will give you the HTTP token after you have supplied the name and username for your bot. 
The token is used to build functionality for your bot via the Telegram API.

Step 3: Connect to the Telegram API via Python
First, we will be installing a couple of Python libraries that will allow us to easily interact with the Telegram API.

Download above python files save it in a folder & open it in VS Code. Ensure path is set in your local enviroment variables. Latest python is installed as well as extension in VS Code. We need to install several files such as pip packages, telegram & python telegram bot.

Type the following in terminal:

py -m pip install
py -m pip install --upgrade pip
py -m install telegram
py -m install python-telegram-bot

Step 4: Editing your list and running the python script.
Edit the bot.py file according to the list of coins you desire. Run tracker.py as well as bot.py after in terminal. 

Step 5:
Type /start in your telegram bot account. If it shows the list, job is done!
