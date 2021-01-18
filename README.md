# Telegram-CLI-Bot
A QJS program to control devices from telegram.

### cli 
```
usage: qjs tgbot [options]  
  -t  --token            Telegram Bot Api Token. https://t.me/BotFather  
  -s  --save             Save the token internally to start the bot in the future without manually provide the token each time.  
  -l  --load             Use the saved token to start the bot.  
  -h  --help             This message.  
  -p  --password         Password to log from Telegram.  
  -v  --verbose          Show basic feedback to the command line interface.  
  -w  --wait             Bot delay in seconds. (Can process multiple messages at once, so you don't need a really low number to don't fallback).  
```
  
### examples
qjs tgbot.js -t 192829292:iqidkwiexampleunvalidtokeniwjwusjwis -s -v  
  
qjs tgbot.js -l -v  
  
qjsc -o tgbot tgbot.js && cp tgbot ~/../usr/bin/  
  
tgbot -l -w 2 -v  

### telegram chat commands
```
/help
/login

/run
/js
/c++
/python
/wait
/shutdown
```

To log in, first write /login and then write the password in a new message.
