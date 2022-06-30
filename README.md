# Telegram File Sender Bot

I had this need to send compressed files/folders through the command line to my telegram bot, and this small script came in handy. 

## Usage

* Find your chat_id by: (your bot token is the token from the botfather )
```bash
curl https://api.telegram.org/bot**YourBOTToken**/getUpdates
```
* Fill chatid and bot_taken variables inside the script

* Send Files by:
```bash
./SendTelegram file1 file2 file3
```
  



## Dependencies
* curl
* tar

I believe these dependencies are present in most linux machines.


## Sources
Some helpful links that made this script possible:
* https://core.telegram.org/bots/api
* https://stackoverflow.com/questions/55470047/how-to-send-file-via-telegram-bot
