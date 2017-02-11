# [MahDiRoO](https://telegram.me/MahDiRoO)

**An advanced and powerful administration bot based on NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/RoO9214/FuckSpaM.git
cd FuckSpaM
chmod +x mahdiroo.sh
./mahdiroo.sh install
./mahdiroo.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone htt https://github.com/Beyps://github.com/RoO9214/FuckSpaM.git && cd FuckSpaM && chmod +x mahdiroo.sh && ./mahdioo.sh install && ./mahdiroo.sh
```

* * *

### Sudo And Bot
After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    302119953,
    0,
    YourID
  }
```
add your bot ID at line 4 and add your ID at line 87 in bot.lua
add your ID at line 2 in tools.lua
Then restart the bot.
