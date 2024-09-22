# Telegram-Bot

Build a TeleGram Bot (NAWAAB) that can help you to resolve your queries for day to day task. It uses telegram-bot-api which we is connected code using dispatcher from aiogram library. It sends the query to GPT using openai-api-key and displays the answer recieved. 


## How To Use
1. Clone the repository.
2. Open it in your IDE.
3. Create a virtual environment (conda create -p name python==3.7.7 -y).
4. Create a .env file and and save your openai-api-key and telegram-bot-api key in it.
     TELEGRAM_BOT_API="your telegram-bot-api"
     OPENAI_API_KEY = "your openai-api-key"
5. install all the requirements by using the command (pip install -r requirements.txt)
6. Open Terminal and run (python telebot.py)

## Techstack
1.python version = 3.7.4
2.Openai
3.Aiogram 
4.Dotenv
