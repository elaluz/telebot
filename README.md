# telebot
criar um telechat
$ export BOT_API_TOKEN="<495885769:AAGWlOW43XKRrdAeum1RuP6SyM2OH-qqahA>"
import os
token = os.environ['BOT_API_TOKEN']
@bot.message_handler(commands=['start', 'help'])
def send_welcome(message):
    bot.reply_to(message, u"Olá, bem-vindo ao bot!")
