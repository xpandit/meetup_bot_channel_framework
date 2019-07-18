## Create a Slack Channel

In order to connect you bot to Slack you need to have a slack account.

After Login you can go to https://api.slack.com/apps

In here you create a app

![create bot](screens/Channel/1.JPG)

A popup will appear, so you can add the app name and the workspace
![create bot](screens/Channel/2.JPG)

After creation go to OAuth & Permissions and add the redirect
![create bot](screens/Channel/3.JPG)

In the Bot Users, click a new Bot User
![create bot](screens/Channel/4.JPG)

Fulfill the display name of the bot
![create bot](screens/Channel/5.JPG)

Go to event Subscription and add the request url https://slack.botframework.com/api/Events/{YourBotHandle}

To know your bot handle go here https://dev.botframework.com/bots
![create bot](screens/Channel/6.JPG)

After add the request URL subscribe the following events
![create bot](screens/Channel/7.JPG)

Go to Interactive Components and add the Following Request URL https://slack.botframework.com/api/Actions
![create bot](screens/Channel/8.JPG)

Select the Basic Information tab and scroll to the App Credentials section. Copy the credentials, it will be necessary in the channel of the web app bot
![create bot](screens/Channel/9.JPG)

In your azure account, go to the Channels in the Web App Bot
![create bot](screens/Channel/10.JPG)

Click Save and confirm you identity.
![create bot](screens/Channel/11.JPG)

Go to your slack workspace, click in your app bot and test you bot
![create bot](screens/Channel/12.JPG)


Now, let's [Create a slack Channel](https://github.com/xpandit/landingjobs_cognitiveservices/blob/master/CreateIntent.md)
