## Import LU to LUIS

go to your app in luis, and go to the Review endpoint utterances.
You can see the utterances that you made, but with no model associated.

![create bot](screens/BotFramework/15.JPG)

That is because you don't have any entities

![create bot](screens/BotFramework/16.JPG)

Go to Manage, then versions.

![create bot](screens/BotFramework/17.JPG)

Select the FlightBooking.json present in your solution, in the cognitiveModel folder. Select a new version number

![create bot](screens/BotFramework/18.JPG)

After import, you can see that some intents appear in the review endpoint utterances, you can add some to the model.

![create bot](screens/BotFramework/19.JPG)

Now, Run your project again with the bot emulator, and click in the LUIS trace. Now you can see the intents.

![create bot](screens/BotFramework/20.JPG)
