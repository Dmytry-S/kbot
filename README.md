# kbot
This is telegram bot t.me/_bot
If you want to create new bot
You should have account in Telegram
Find BotFather in Telegram
Click /newbot
Create name for bot
Create username
Copy token, open project and add it into your code in variable TELE_TOKEN
build project with "go build -ldflags "-X="<git link to project>/cmd.appVersion=V<version number>"
launch bot with "./kbot start"
in Telegram you can send comands in bot and get logs in terminal
