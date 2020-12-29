# Bloopsbot - offline quizzes
```
___.   .__                                 ___.           __   
\_ |__ |  |   ____   ____ ______  ______   \_ |__   _____/  |_ 
 | __ \|  |  /  _ \ /  _ \\____ \/  ___/    | __ \ /  _ \   __\
 | \_\ \  |_(  <_> |  <_> )  |_> >___ \     | \_\ (  <_> )  |  
 |___  /____/\____/ \____/|   __/____  >____|___  /\____/|__|  
     \/                   |__|       \/_____/   \/                                                                          
```

## What is bloopsbot?
Well, this is a telegram bot 🤖 for organizing quizzes similar to quizzes in tiktok, where you need to
30 seconds name a few words from the proposed categories at a random letter. The bot is organizing, counting points, and you play with your friends

## Location
You can use it here -> [bloops in Telegram](https://t.me/bloops_bot)

## Why?
🎄🎄🎄 The project was created for playing with the family during the holidays. This is just fun

## Features
* 🕹️ Offline format for small get-togethers with friends or parties
* 🎲 Quiz format with clear rules, in 30 seconds you need to name a few words for the dropped out letter
* 💎 Bloops are additional tasks that you can get, maybe they will amuse you or increase the number of points
* 👯 You can even add players without telegrams  
* 👽 Players have profiles, simple statistics are kept
* 👨 Simple interface, you can create a game in a few steps and customize it for yourself, for example, add or remove blues, vote or enable your categories
* 🖥️‍ You can use a CLI or deploy docker container
* 👨‍🔬🥽🧪 Key-value embedded db, when moving the application to another location, you just need to copy the db file and run the application
* 🚀 Without complex configuration, compiled and started

## Play
🚀 [PLAY](https://t.me/bloops_bot)

## Language and localization
No😔, only in Russian

## Site
🖥🖱🌍 [bloops.fun](https://bloops.fun)

## Development
This is shitty code, I know there is no testing in it, but this is my little hackathon to get it done quickly for the holidays

## 🚀 Quick start
For CLI version make 
1. *Clone repo*
```
$ git clone https://github.com/robotomize/bloop.git
```
2. *Build CLI application*
```
$ cd bloop
$ go build cmd/bloop-cli
```
3. *Register your bot token* [bot father](https://t.me/BotFather)
```
$ ./bloop-cli
```

To build a docker image run the following commands
```
$ docker build -e BLOOP_TOKEN="BOT_TOKEN" -it . 
```
Or you can build the service by adding the bot token to the environment variables
```
$ go build cmd/bloop-srv
```
## Contact
tg: [@robotomize](https://t.me/robotomize)