---
title: 'Creating a new Telegram bot'
menuTitle: 'Creating a new bot'
description: ''
category: 'Quickstart'
fullscreen: true 
position: 20
---

## New bot creation
Go to the [@BotFather](https://t.me/botfather) app on Telegram.

Send `/newbot`, to start creating a new Bot and setting its name and username.

<img src="screenshots/new-bot.jpg" />

Take note of the bot `token`.

<img src="screenshots/new-bot-token.jpg" />

### Join groups permission

To allow the bot to join Telegram groups, use the `/setjoingroups` command in @BotFather:

<img src="screenshots/new-bot-joingroups.jpg" />

### Privacy
Now you need to choose how much the bot will be able to read from the chats. Send `/setprivacy` command to @BotFather, and select your bot privacy:

  - **enable**: to handle only `/` commands handling
  - **disable**: to allow the bot to read all messages sent to the chat

    <img src="screenshots/new-bot-setprivacy.jpg" />
