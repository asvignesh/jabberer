**Move to github** https://github.com/jdkcn/jabberer

_For sample Jabber bot use._

## Usage ##

  * checkout the code.

```
svn checkout http://jabberer.googlecode.com/svn/trunk/ jabberer
```
  * copy the sample property file bot.properties.sample to bot.properties, and change the value for yourself.

```
cp src/main/resources/bot.properties.sample src/main/resources/bot.properties
```

  * run the bot

```
sh jabberer.sh
```

## bot.properties ##

```
#The gtalk username
username=jabberer.bot@gmail.com
#The password
password=blabla
#The bot's online message
bot.status.message=Just a sample java jabber bot.
#Whether send offline message or not
send.offline.message=false
```