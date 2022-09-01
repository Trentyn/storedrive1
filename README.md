## Configs:
- `API_ID` - Get this from [Telegram.org](https://my.telegram.org)
- `API_HASH` - Get this from [Telegram.org](https://my.telegram.org)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `BOT_USERNAME` - You Bot Username. *(Without [@])*
- `DB_CHANNEL` - A Telegram Channel ID.
	- Make a Channel for Storing Files. We will use that as Database. Channel must be Private! Else you will be Copyright by [Telegram DMCA](https://t.me/dmcatelegram)!
- `BOT_OWNER` - Bot Owner UserID
	- Put your Telegram UserID for doing Broadcast.
- `DATABASE_URL` - MongoDB Database URI
	- This for Saving UserIDs. When you will Broadcast, bot will forward the Broadcast to DB Users.
- `UPDATES_CHANNEL` - Force Sub Channel ID *(Optional)*
	- ID of a Channel which you want to do Force Sub to use the bot. 
- `LOG_CHANNEL` - Logs Channel ID
	- This for some getting user info. If any new User added to DB, Bot will send Log to that Logs Channel. You can use same DB Channel ID.
- `FORWARD_AS_COPY` - Value should be `True` or `False` *(Optional)*
	- If `True` all messages will be forwarder *As Copy*. If `False` all messages will be forwarder with Forward Tag.
- `BROADCAST_AS_COPY` - Value should be `True` or `False` *(Optional)*
  	- Broadcast with Forward Tag or as Copy.*(Without Forward Tag)*
- `BANNED_USERS` - Banned unwanted members
         - Put all banned user IDs & Separate with space.
- `BANNED_CHAT_IDS` - All Banned Channel IDs *(Optional)*
	- Put all banned channel IDs & Separate with space.

### Deploy Now:
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Trentyn/storedrive1)

## Commands:
```
start - start the bot
clear_batch - Clear User Batch Files
status - Show number of users in DB [Owner Only]
broadcast - Broadcast replied message to DB Users [Owner Only]
ban_user - [user_id] [ban_duration] [ban_reason] Ban Any User [Owner Only]
unban_user - [user_id] Unban Any User [Owner Only]
banned_users - Get All Banned Users [Owner Only]
```

