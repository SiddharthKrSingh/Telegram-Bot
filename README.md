# Telegram-Bot

The NAWAAB Telegram bot is designed to assist in resolving day-to-day task-related queries. It leverages the Telegram Bot API for communication and interacts with users through the aiogram library, utilizing its Dispatcher to handle updates and dispatch commands efficiently.

The bot is integrated with OpenAI's GPT models via the OpenAI API, where user queries are forwarded for processing. Upon receiving the response from the GPT model, NAWAAB parses and displays the result to the user, providing intelligent and context-aware answers to task-based inquiries.


<p align="center">
  <img src="https://github.com/SiddharthKrSingh/Telegram-Bot/blob/main/bot-image.jpg" width="350" title="hover text">

</p>

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
1. python version = 3.7.4
2. Openai
3. Aiogram 
4. Dotenv
