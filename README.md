# MILLIE BOT
Very Sempil Bot Auto Filter bot
##[![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=welcome+To+MILLIE-FILTER-BOT!;created+by+TEAM+HACKER-JT!;A+simple+autofilter+Bot!;Auto+filter+with+double+button!;start+message+with+pic!;and+all+futures!)
</p>
# 𝐂𝐋𝐈𝐂𝐊 𝐁𝐄𝐋𝐎𝐖 𝐈𝐌𝐀𝐆𝐄 𝐓𝐎 𝐃𝐄𝐏𝐋𝐎𝐘👇👇👇


[![Deploy](https://telegra.ph/file/93729208cb4fb5f1f4300.jpg)](https://heroku.com/deploy?template=https://github.com/Blesson-23/AnnaBen_robot)

- [x] Auto Filter
- [x] Manuel Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Fun mode
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel

















## DEPLOY ON HEROKU
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Blesson-23/AnnaBen_robot)


### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](https://github.com/EvamariaTG/evamaria/blob/master/info.py) for more

## Note
* Currently [API used](http://www.omdbapi.com) here is allowing 1000 requests per day. [You may not get posters if its crossed](https://t.me/ThankTelegram/910168). 
Once a poster is fetched from OMDB , poster is saved to DB to reduce duplicate requests.

## Admin commands
```
channel - Get basic infomation about channels
total - Show total of saved files
delete - Delete file from database
index - Index all files from channel.
logger - Get log file
```
