# Telegram-CLI-Bot
A Quickjs/Node.js console bot to control devices from telegram.

### Download
git clone https://github.com/StringManolo/Telegram-CLI-Bot.git

### Install Termux
pkg install quickjs && cd Telegram-CLI-Bot && qjs tgbot.js



### Run
```
usage: qjs/node tgbot [options]  
  -t  --token            Telegram Bot Api Token. https://t.me/BotFather  
  -s  --save             Save the token internally to start the bot in the future without manually provide the token each time.  
  -l  --load             Use the saved token to start the bot.  
  -h  --help             This message.  
  -p  --password         Password to log from Telegram.  
  -v  --verbose          Show basic feedback to the command line interface.  
  -w  --wait             Bot delay in seconds. (Can process multiple messages at once, so you don't need a really low number to don't fallback).  
```
  
### examples quickjs
qjs tgbot.js -t 192829292:iqidkwiexampleunvalidtokeniwjwusjwis -s -v -p miPasswordToLogin
  
qjs tgbot.js -l -v -p miPasswordToLogin
  
qjsc -o tgbot tgbot.js && cp tgbot ~/../usr/bin/  
  
tgbot -l -w 8 -v -p miPasswordToLogin

### examples node
node tgbot.js -t 192829292:iqidkwiexampleunvalidtokeniwjwusjwis -s -v -p miPasswordToLogin
  
node tgbot.js -l -v -w 8 -p miPasswordToLogin
  
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
