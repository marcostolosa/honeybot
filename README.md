# 🍯 honeybot py [ [docs](https://pyhoneybot.github.io/honeybot/) ]

<div align="center">

<img src="./assets/honeybot_real.png" width="64" />

[![PyPI version](https://badge.fury.io/py/honeybot.png)](https://badge.fury.io/py/honeybot)
[![First Timers Only](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://www.firsttimersonly.com/)
![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-pink.svg)
![Made in Moris](https://img.shields.io/badge/Made%20in-Moris-green.svg)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/6329/badge)](https://bestpractices.coreinfrastructure.org/projects/6329)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/pyhoneybot/honeybot/badge)](https://api.securityscorecards.dev/projects/github.com/pyhoneybot/honeybot)

<hr>
🇲🇺 🇺🇸 🇨🇦 🇦🇷 🇮🇳 🇬🇧 🇬🇬 🇧🇷 🇸🇽 🇵🇱 🇩🇪 🇲🇼 🇲🇦

</div>
<div align="center">

[![Open Source Helpers](https://www.codetriage.com/pyhoneybot/honeybot/badges/users.svg)](https://www.codetriage.com/pyhoneybot/honeybot)
[![Discord](https://img.shields.io/badge/chat%20on-discord-green.svg)](https://discordapp.com/invite/E6zD4XT)

</div>

# Table of Contents

- [📮 About](#-about)
- [🕹 Project Motivation](#-project-motivation)
- [✂ Current Features](#-current-features)
- [:mountain: GUI clients](#mountain-gui-clients)
- [⌚ Current Plugins](#-current-plugins)
- [⚡ Quickstart](#-quickstart)
- [💻 Seeing The Bot In Action](#-seeing-the-bot-in-action)
- [Docker](#docker)
- [🔧 Plugins Development](#-plugins-development)
- [📃 Contributing Guide](#-contributing-guide)
- [🔌 Todo Plugins](#-todo-plugins)
- [☑ Allowing Plugins](#-allowing-plugins)
- [:thought_balloon: Project Testimonials](https://github.com/deadex-ng/honeybot/blob/readme-fix/TESTIMONIALS.md)
- [📧 Contact (Including vulnerabilities)](#-contact-including-vulnerabilities)
- [🖊 Credits](#-credits)

## 📮 About

HoneyBot is a python-based IRC bot. (**python3.7**) | If you want to just run the bot, go to the [quick start section](https://github.com/pyhoneybot/honeybot#-quickstart)

> HoneyBot is my first time collaborating to an open source project and I'm loving it. Before discovering HoneyBot, I was very intimidated on the idea of working with other people and had no idea what an IRC even was. Now I realize how much fun and rewarding it is to work together on a project with dedicated and friendly individuals. The documentation is easy to follow and everyone is super helpful. I highly recommend any new programmer who want to contribute on an open source project to try out HoneyBot. Personally I enjoy working on this project more than my own schoolwork. --[@RiceAbove](https://github.com/RiceAbove)

Feel free to contribute to the project!

## 🕹 Project Motivation

Implementing the project in Java was weird, py's connect was sleek. Thus, the project stack was shifted over to Python.
If you can think of any features, plugins, or functionality you wish to see in the project. Feel free to add it yourself, or create an issue detailing your ideas. We highly recommend you attempt to implement it yourself first and ask for help in our [discord server](https://discord.gg/E6zD4XT) !

Psst. Since I learnt py through this bot, we decided to keep a new-comers friendly policy. Feeling lost? Just ping.

## ✂ Current Features

- 🍬 OOP architecture
- 🛰️ keyword parameters
- 🌵 password security with config file [disabled for now]
- 🔌 now with plugins

## :mountain: GUI clients

GUI clients are used to manage plugins, launch bot as well as specify credentials.

- [CPP client](https://github.com/pyhoneybot/cpp-client) by [@Macr0Nerd](https://github.com/Macr0Nerd)

## ⌚ Current Plugins

| Plugin                 | Description                                                                           | Contributor                                                                                              |
| ---------------------- | ------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| 💎 bitcoin             | Get price of bitcoin                                                                  | [@Macr0Nerd](https://github.com/Macr0Nerd)                                                               |
| ⏲ caesar cipher        | Encode your text                                                                      | [@kylegalloway](https://github.com/kylegalloway)                                                         |
| 🔢 calc                | Evaluates maths expressions                                                           | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ)                                                     |
| 📐 maths               | Trigonometry & random number generator                                                | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ)                                                     |
| 🍃 conv sniff          | Set triggers like how many times a word occur for one or more words and send response | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ)                                                     |
| ❄ greet                | Demo plugin                                                                           | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ)                                                     |
| ⛓ installed_modules    | Checks dependencies installed                                                         | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ)                                                     |
| 🕶 joke                 | Get random joke                                                                       | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ), [@colbyjayallen](https://github.com/colbyjayallen) |
| ❓ self Trivia         | Random trivia                                                                         | [@ajimenezUCLA](https://github.com/ajimenezUCLA)                                                         |
| 💢 username            | Username generator                                                                    | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ), [@sseryani](https://github.com/sseryani)           |
| 📜 quotes              | Inspirational quotes                                                                  | [@German-Corpaz](https://github.com/German-Corpaz)                                                       |
| 📖 dictionary          | Returns meaning of word                                                               | [@iamnishant14](https://github.com/iamnishant14)                                                         |
| 🔣 password generator  | The name tells it all                                                                 | [@iamnishant14](https://github.com/iamnishant14)                                                         |
| 🐜 debug               | Prints all parameters passed to bot                                                   | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ)                                                     |
| 📚 wikipedia           | Returns a wikipedia article                                                           | [@Macr0Nerd](https://github.com/Macr0Nerd)                                                               |
| 🗿 translate           | Google translate plugin                                                               | [@a-deeb](https://github.com/a-deeb)                                                                     |
| 📑 test                | Runs tests                                                                            | [@Abdur-rahmaanJ](https://github.com/Abdur-rahmaanJ)                                                     |
| ⛅️ weather            | Returns weather info for a given location                                             | [@Macr0Nerd](https://github.com/Macr0Nerd)                                                               |
| ✉️ mail                | Send emails within the chat                                                           | [@TannerFry](https://github.com/TannerFry)                                                               |
| 🕴️ hangman             | Play hangman in the chat                                                              | [@JustinWalker4179](https://github.com/justinwalker4179)                                                 |
| 🎂 age                 | Takes in birthday and outputs age                                                     | [@JustinWalker4179](https://github.com/justinwalker4179)                                                 |
| ✔️ fact                | Returns a random fact                                                                 | [@JustinWalker4179](https://github.com/justinwalker4179)                                                 |
| 🔍 google              | Returns three search results from google                                              | [@JustinWalker4179](https://github.com/justinwalker4179)                                                 |
| 📮 send message        | Sends a message to another channel                                                    | [@JustinWalker4179](https://github.com/justinwalker4179)                                                 |
| 📝 log                 | Logs the chat into a log file                                                         | [@RiceAbove](https://github.com/RiceAbove)                                                               |
| 🚪 joins               | Greets everyone who joins the channel                                                 | [@RiceAbove](https://github.com/RiceAbove)                                                               |
| 📅 date                | Posts the current date                                                                | [@RiceAbove](https://github.com/RiceAbove)                                                               |
| 🕵️‍ riddle             | Returns a random riddle                                                               | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 🗞 news                 | Gets the top 10 headlines from bbc world news                                         | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 📝 horoscope           | Gets your daily horoscope for your starsign                                           | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 💵 currency converter  | Converts currencies                                                                   | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 🔫 russian_roulette    | May or may not kick you off the channel                                               | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 🏨 monopoly            | Honeybot now supports the world's worst game!                                         | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| ⚽️ transfer_rumour    | Shows the day's transfer rumours                                                      | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 🃏 blackjack/21        | Play 21 on honeybot!                                                                  | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 🤒 corona              | Get the latest news on coronavirus with honeybot!                                     | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 📖 diary               | Keep a diary with honeybot                                                            | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 🛩 flight               | Gets flight info from flightradar24                                                   | [@AngeloGiacco](https://github.com/AngeloGiacco)                                                         |
| 🎲 roll                | Rolls a dice                                                                          | [@GlennToms](https://github.com/GlennToms)                                                               |
| ❓ help                | Show link to plugin's information page                                                | [@edumello](https://github.com/edumello)                                                                 |
| ✅ channeljoin         | Join command for bot                                                                  | [@marceloyb](https://github.com/marceloyb)                                                               |
| :page_with_curl: comic | Returns a random comic                                                                | [@mboekhold](https://github.com/mboekhold)                                                               |
| 📝 todo                | Makes a to do list                                                                    | [@h-ranjan1110](https://github.com/h-ranjan1110)                                                         |
| 🎱 Magic 8 Ball        | Answer questions using magic 8 ball                                                   | [@ZakariaTalhami](https://github.com/ZakariaTalhami)                                                     |
| 🎟 Random Excuse        | Generates a random excuse for you.                                                    | [@rakeshseal0](https://github.com/rakeshseal0)                                                           |
| 🦆 DuckDuckGo Search   | Search queries in duckduckgo and return abstract.                                     | [@rakeshseal0](https://github.com/rakeshseal0)                                                           |
| 🖼 Random Image         | Returns a random image url.                                                           | [@rakeshseal0](https://github.com/rakeshseal0)                                                           |
| 🛢 URL Shortener        | Shortens a url                                                                        | [@rakeshseal0](https://github.com/rakeshseal0)                                                           |
| 😁 emoji               | Returns emoji meaning                                                                 | [@deadex-ng](https://github.com/deadex-ng)                                                               |
| 🎂 birthday            | Shows birthday match probability on a people group.                                   | [@paulosgf](https://github.com/paulosgf)                                                                 |
| 🏀 basketball          | Shows information about the medals of euroBasket and Basketball world cup             | [@kefthymic](https://github.com/kefthymic)                                                               |
| 🎬 movies_imdb         | Returns certain information about a certain movie or shows 250 all time best movies   | [@ZoeyKats](https://github.com/ZoeyKats)                                                                 |
| ⛩️ anime               | Returns certain information about the top 100 anime                                   | [@cdkontos](https://github.com/cdkontos)                                                                 |

## ⚡ Quickstart

setup

```bash
mkdir botx
cd botx
python -m venv venv
venv\scripts\activate # or source venv/bin/activate for linux
python -m pip install honeybot

```

run

```bash
honeybot init
honeybot run
```

in settings/CONNECT.conf

```
[INFO]

server_url = irc.libera.chat
port = 6667
name = appinventormuBot
```

In settings/PLUGINS.conf listed plugins under plugins/downloaded will load. Plugins listed under plugins/core are auto loaded.

## 💻 Seeing The Bot In Action

Get an IRC client

- Web: [Kiwiirc](https://kiwiirc.com) (easy)
- Desktop: [Hexchat](https://hexchat.github.io)
- Android: [Revolution IRC](https://github.com/MCMrARM/revolution-irc)

configure

```
port: 6667
url: irc.libera.chat
```

then join channel `#ltch`

you should see the bot as hbot ... or as it's name is in [settings](https://github.com/pyhoneybot/honeybot/blob/master/src/honeybot/settings/CONNECT.conf)

## Docker

**Building Docker image**

Change SERVER, PORT and NICKNAME variables to match your preferences

```
docker build -t "honeybot/honeybot:6.0.2" .
```

**Running Docker image**

```
docker run -d --name=honeybot honeybot/honeybot:v6.0.2 honeybot run
```

## 🔧 Plugins Development

Each plugin has a folder named after it. In it there is a file called main.py. In each there is a class called Plugin.

```python
# -*- coding: utf-8 -*-

class Plugin:
    def __init__(self):
        pass

    def run(self, incoming, methods, info, bot_info):
        try:
            if info['command'] == 'PRIVMSG' and info['args'][1] == '.hi':
                methods['send'](info['address'], 'hooo')
        except Exception as e:
            print('woops plugin error ', e)
```

we see four parameters being passed to the run method `, incoming, methods, info, bot_info)`

#### parameter1: incoming

`incoming` is the raw line and is not used except if you are not satisfied with the already provided methods

#### parameter2: methods

`methods` is a dictionary of methods to ease your life. a quick look at [main.py](https://github.com/pyhoneybot/honeybot/blob/master/src/honeybot/api/main.py) reveals

```python
def methods(self):
        return {
                'send_raw': self.send,
                'send': self.send_target,
                'join': self.join
                }
```

where `send_raw` allows you to send in any string you want, thereby allowing you to implement any irc protocol from scratch

but, for most uses, `send` allows you to send a message to an address `methods['send']('<address>', '<message>')`. using it in conjunction with info parameter allows you to send messages where it came from, in pm to the bot or in a channel. you can however hardcode the address.

`join` allows you to join a channel by `methods['join']('<channel name>')`

#### parameter3: info (meaning message info)

for a normal run, info produces

```python
{
'prefix': 'appinv!c5e342c5@gateway/web/cgi-irc/kiwiirc.com/ip.200.200.22.200',
'command': 'PRIVMSG',
'address': '##bottestingmu',
'args': ['##bottestingmu', 'ef']
}
```

hence if you want messages, `messages = info['args'][1:]` or the first word if you want to check for command will be `info['args'][1]`

**use example**

- the command info is used in the join channel plugin to detect a join command and greet the user who just joined

### bot info

bot_info returns info about the bot

```python
        return {
            'name': self.name,
            'special_command': self.sp_command,
            'required_modules': self.required_modules,
            'owners': self.owners,
            'time': self.time,
            'friends': self.friends
        }
```

so that in run method you can access those.

**use example**

- For example, the time info is used in the uptime plugin by minussing it from the current time to get time bot has been running.
- The required modules is used in the installed plugin to determine what required plugin the bot runner did not install

#### wrapping up

hence

```python
if info['command'] == 'PRIVMSG' and info['args'][1] == '.hi':
    methods['send'](info['address'], 'hooo')
```

from above means

```
if message received == .hi:
    send(address, message)
```

## 📃 Contributing Guide

<https://pyhoneybot.github.io/honeybot/How_Tos/contributing.html>

- don't forget to add your country flag here after accepted PR. i'll have to hunt it down on your profile if not.
- make sure to follow PEP8

Check out [Contributing](https://github.com/pyhoneybot/honeybot/blob/master/CONTRIBUTING.md) to get started on contributing.

## 🔌 Todo Plugins

- [x] 💐 humour
- [x] 🌨️ weather
- [x] ✉️ mail
- [x] 🎛️ maths
- [ ] 📥 pm when user online
- [ ] Random Colour

## ☑ Allowing Plugins

**Plugins available**
<https://pyhoneybot.github.io/honeybot/plugins.html>

in settings/settings.toml, add the plugin to allow! 

```toml
[PLUGINS]

downloaded = ["greet",] # Downloaded plugins to load
```

## 📧 Contact (Including vulnerabilities)

### Email

- Abdur-Rahmaan Janhangeer | arj.python@gmail.com

## 🖊 Credits

- [@arwinneil](https://github.com/arwinneil), "Open Source" and "Made In Moris" badges
