# Telegram Agent Notifier 

Telegram WebHook integration, it sends initial beacon agent notification over to Telegram

# How to configure the Telegram Bot?


1. Open Telegram and search "BotFather" in the search bar. This is the official bot that allows you to create other bots.

2. Create new bot: /newbot

3. Choose a name for your bot: ScriptNotifier

4. Choose a username for your bot that must end with "_bot": script_notifier_bot

5. Once the bot is created, you will have a long string: this is the TOKEN-ID

6. The bot will send you messages on a specific chat that you need to create. Go to Telegram search bar, on your smartphone, and search your bot (e.g. ScriptNotifier). Then, start the bot: /start

7. Finally, search for your CHAT-ID by going to the bot webpage: https://api.telegram.org/bot[TOKEN-ID]/getUpdates

# How to configure it to work with Cobalt Strike?

1. Edit Telegram-Notifier.cna and change the **$TelegramBotToken**  and **$TelegramChatID**  environmental variables to match your Telegram Bot Token ID & Channel ID

2. Load the Telegram-Notifier.cna on Cobalt Strike


#  Telegram notification on Beacon Initial


![Initial Detonation Demo](https://i.ibb.co/Kq4wrtx/Telegram-Initial-Detonation.png)

