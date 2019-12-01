# Telegram File Sender Bot

I had this need to send compressed files/folders through the command line to my telegram bot, and this small script came in handy. 

## Usage

* Find your chat_id by: (your bot token is the token from the botfather )
```bash
curl https://api.telegram.org/bot**YourBOTToken**/getUpdates
```
  

* Fill chatid and bot_taken variables inside the script

## Dependencies
* curl
* tar

I believe these dependencies are present in most linux machines.
