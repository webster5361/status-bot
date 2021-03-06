# Mumblerines Squad Server Status Bot

[![Greenkeeper badge](https://badges.greenkeeper.io/Odinthewanderer/status-bot.svg)](https://greenkeeper.io/)
[![David](https://img.shields.io/david/Odinthewanderer/status-bot.svg?maxAge=3600)](https://david-dm.org/Odinthewanderer/status-bot)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/957f59e855764ae3ae937b17c93f372f)](https://www.codacy.com/app/Odinthewanderer/status-bot?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Odinthewanderer/status-bot&amp;utm_campaign=Badge_Grade)
[![Build Status](https://travis-ci.org/Odinthewanderer/status-bot.svg?branch=master)](https://travis-ci.org/Odinthewanderer/status-bot)

## REQUIREMENTS
Node version 7+

RECOMMENDED Node version 8+

## INSTALLATION
To begin, clone the repository from [HERE!](https://github.com/Odinthewanderer/status-bot.git)

Issue the command:

`npm install`

This will install all required dependencies.

## CONFIGURATION
`mv lib/config.json.example lib/config.json`

Edit this file to include your bot token, client id, discord id, and desired prefix (default prefix is !).

## STARTUP

`node bot.js`

## KNOWN BUGS

1. ~There is a small issue that only occurs on the very first startup. You will encounter an error. Just Ctrl+C to kill it and restart the bot. You will never see this error again.~ [ISSUE 1](https://github.com/Odinthewanderer/status-bot/issues/1) -- ISSUE CLOSED
2. ~Occassionally the images will take longer than expected and will paste an incomplete image into the chat. Attempt to rerun the !status command again.~ [ISSUE 2](https://github.com/Odinthewanderer/status-bot/issues/2) -- ISSUE CLOSED
