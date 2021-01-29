# py-telegram-bot-alcohol

(Last Updated: 29 January 2021)

Using Python to create a Telegram bot that informs the user of details of a cocktail based on an appropriate user input. You can try my Telegram bot @alcoholick_bot.

Where do I host my Python codes? https://www.pythonanywhere.com/

Create a free account.
Upload your Python codes as a File.
Create a Bash Console.
Wait for Bash Console to load. Then, type "python your_python_file_name.py" and run.
Resource: https://www.youtube.com/watch?v=jhFsFZXZbu4&t=1s

Cocktail API information:
- Resource: https://www.thecocktaildb.com/api.php
- I am using the developer test key '1' as the API key. You can sign up to Patreon if you would like a production API key (so that you could, for instance, release publicly on an appstore).

How does the bot work?
For example, if user inputs "margarita" to the bot, the resulting JSON object is https://www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita. Next, the bot will randomly select a drink from the list of drinks to return to the user.

There is no command for this bot.
