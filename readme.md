## Simple telegram bot skeleton for java

### Created using:
- maven
- java 11
- telegram bot library for java(https://github.com/rubenlagus/TelegramBots)

### Bot functionality:
- Responds to user with the same text(echo effect)

### Run:
1. Create bot via BotFather (`t.me/BotFather`)
2. Specify `token` and `username` in `SimpleEchoBot.java`
3. Run `Application.main()`
4. Wait for message `Telegram bot is ready to accept updates from user......`
5. Now navigate to your bot and try to send some text to the bot

### Play with bot
`SimpleEchoBot.java` contains `onUpdateReceived()` - entrypoint, in which bot receives messages from Telegram.
Try to look at the code and play with it.
