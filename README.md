## Overview
- Discord bot that gets coinpoker's hot and cold wallet balances.
![botping](botping.png)

## Setup
- `npm install` to install dependencies
- Fill in proper `.env` variables 
    - Alchemy API key and HTTPS link to fetch on chain data, make sure app is ethereum mainnet. 
    - Discord bot token when creating bot.
- This tutorial is great for setting up bot in discord developer application : https://www.youtube.com/watch?v=KZ3tIGHU314

## Hosting
Hosting Your Bot: Decide where to host your bot for 24/7 uptime.
Vercel: More front-end and serverless functions oriented but possible to run bots if they are not resource-intensive.
Heroku: Offers a free tier and is quite popular for small Discord bots.
Glitch: Also a popular choice for hosting simple bots.

Query limits to avoid abuse. (For discord and alchemy API).