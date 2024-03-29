<div align="center">
  <img width="128" height="128" src="./images/logo.png">
  <h1>Hu tao bot</h1>
  <p>Discord bot for get profile, abyss, realtime, etc. from Genshin Impact API.</p>
  <a href="https://hutao-bot.m307.dev/invite">
    <img src="./images/svg/Invite-Button.svg" />
  </a>
  <a href="https://hutao-bot.m307.dev">
    <img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white" />
  </a>
</div>

# Feature
- ✅ View profile data.
- ✅ View realtime data.
- ✅ View Spiral Abyss current data.
- ✅ View all character's list, info and showcase data.
- ✅ Auto daily checkin.
- ✅ Wish banner (From 1.0 - now)
- ✅ Redeem code.

# Tools
- [Python](https://www.python.org/)
- [Redis](https://redis.io/)
- [MongoDB](https://www.mongodb.com/)

# Library (Public)
## Discord bot
- [nextcord](https://github.com/nextcord/nextcord)
- [table2ascii](https://github.com/DenverCoder1/table2ascii)

## WebAPI 
- [FastAPI](https://fastapi.tiangolo.com/)

## Genshin Impact API
- [genshin.py](https://github.com/thesadru/genshin.py)
- [enkanetwork.py](https://github.com/mrwan200/enkanetwork.py)

## Tools
- [aioredis](https://aioredis.readthedocs.io/en/latest/)
- [aiohttp](https://docs.aiohttp.org/en/stable/)
- [PyJWT](https://pyjwt.readthedocs.io/en/stable/)
- [pymongo](https://github.com/mongodb/mongo-python-driver)
- [RSA](https://stuvel.eu/software/rsa/)
- [Sentry-SDK](https://docs.sentry.io/clients/python/)

# Library (Private)
- Slash command
- ~~[Genshin Account (Monify from genshin.py)](https://github.com/Hu-tao-bot/genshin.py)~~ **(Deprecated)**
- FastAPI JWT (Monify from FastAPI JWT Auth)
- [FastAPI RateLimit (Monify from FastAPI Limiter)](https://github.com/long2ice/fastapi-limiter) 
- ~~Error tracking~~ **(Deprecated)**

# Screenshot
You can see screenshot in [Screenshots](./screenshots/README.md) folder.

# FAQ
## Q: How to get profile, realtime, abyss, etc. from Genshin Impact data?
A: I have to use [genshin.py](https://github.com/thesadru/genshin.py) library to get data. If you want to see how it works, please see [genshin.py docs](https://thesadru.github.io/genshin.py/).

## Q: How to get character stats (Showcase) data from Genshin Impact data?
A: It's use [Enka.Network](https://enka.network) for fetch character stats data.

## Q: It's secure?
A: Yes, It's using RSA to encrypt data and save to database.

## Q: I want to login with third party account (Example: Facebook, Google, etc.). How to do it?
A: In Third party account block access another URL login. **If you want login with third party account, you must have link email and password to your account.** 

## Q: I want to access with my account. How to do it?
A: You can go to site https://hutao-bot.m307.dev to login genshin account.

## ~~Q: I can't invite bot to my server.~~
~~A: The bot is now rate limited invite from Discord. Please wait 2 - 4 week to waiting get verified bot.~~
**( Update: Bot has got verified so you can invite me to your server. 🥳🎉 [ 29 March 2022 ] )**

## Q: Why character's list has shown only 8 character?
A: Because you have login with UID or HoyolabID. If you want to see all character's list, you have to login with Token or E-mail & Password

## Q: I got unknow error when I use command.
A: Please capture error screenshot and send to [Discord server](https://shirabot.xyz/go/hutaosupport)

## Q: I want to know more about me.
A: Please contact via email at [me@m307.dev](mailto:me@m307.dev)

# License
[MIT](./LICENSE)

<img width="256" height="256" src="https://c.tenor.com/yaQtPhN-l14AAAAd/hu-tao-genshin.gif">