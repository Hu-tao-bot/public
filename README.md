<div align="center">
  <img width="128" height="128" src="./images/logo.png">
  <h1>Hu tao bot</h1>
  <p>Discord bot for get profile, abyss, realtime, etc. from Genshin Impact API.</p>
</div>

# Feature
- ✅ View profile data.
- ✅ View realtime data.
- ✅ View Spiral Abyss current data.
- ✅ View all character's list and info data.
- ✅ Redeem code.

# Tools
- [Python](https://www.python.org/)
- [Redis](https://redis.io/)
- [MonogDB](https://www.mongodb.com/)

# Library (Public)
## Discord bot
- [nextcord](https://github.com/nextcord/nextcord)
- [table2ascii](https://github.com/DenverCoder1/table2ascii)

## WebAPI 
- [FastAPI](https://fastapi.tiangolo.com/)

## Genshin Impact API
- [genshin.py](https://github.com/thesadru/genshin.py)

## Tools
- [aioredis](https://aioredis.readthedocs.io/en/latest/)
- [aiohttp](https://docs.aiohttp.org/en/stable/)
- [PyJWT](https://pyjwt.readthedocs.io/en/stable/)
- [pymongo](https://github.com/mongodb/mongo-python-driver)
- [RSA](https://stuvel.eu/software/rsa/)
- [Sentry-SDK](https://docs.sentry.io/clients/python/)

# Library (Private)
- Slash command
- Genshin Account (Monify from genshin.py)
- FastAPI JWT (Monify from FastAPI JWT Auth)
- ~~Error tracking~~ **(Deprecated)**

# Screenshot
You can see screenshot in [Screenshots](./screenshots/README.md) folder.

# FAQ
## Q: How to get profile, realtime, abyss, etc. from Genshin Impact data?
A: I have to use genshin.py library to get data. If you want to see how it works, please see docs [this](https://thesadru.github.io/genshin.py/genshin_api/).

## Q: It's secure?
A: Yes, it's secure. It's using RSA to encrypt data to save in database.

## Q: I want to login with third party account (Example: Facebook, Google, etc.). How to do it?
A: Sorry, I can't do it. Because in Third party account block access another URL login.

## Q: I want to login with my account. How to do it?
A: You can enter site https://hutao-bot.m307.dev to login genshin account.

## Q: I can't invite bot to my server.
A: The bot is now rate limited invite from Discord. Please wait 2 - 4 week to waiting get verified bot.

## Q: I see unknow error message. How to do it?
A: Please contact in Discord server at https://shirabot.xyz/go/hutaosupport

## Q: I want to contact with private message.
A: Please contact with mail at [me@m307.dev](mailto:me@m307.dev)

# License
MIT

<img width="256" height="256" src="https://c.tenor.com/yaQtPhN-l14AAAAd/hu-tao-genshin.gif">