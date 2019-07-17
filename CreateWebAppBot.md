## Creating a Web App Bot

We're going to start with a simple bot and just start conneting the slack to it.


## We'll start preparing the bot

First Create a Web App Bot in [azure](https://portal.azure.com/)

**Remember to use the Basic bot**

![create bot](screens/WebAppBot/1.JPG)


After fulfill all the fields click create


![create bot](screens/WebAppBot/2.JPG)

As you can see 4 components were created:
   - Web App Bot: this is the bot, is this component which will connect to the channels
   - App Service Plan: this is the service plan which all other components will use
   - App Service: In this component is the code to handle the interactions, in other words, is here where the bot framework is.
   - Application Insights: The component responsible to monitor the requests.

![create bot](screens/WebAppBot/3.JPG)

Now, let's [Test the Bot](https://github.com/xpandit/meetup_bot_channel_framework/blob/master/TestWebAppBot.md)


