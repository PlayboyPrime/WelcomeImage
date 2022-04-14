# CONFIG EXPLANATION
***

## Message & Embed

![image](https://user-images.githubusercontent.com/55946112/163333611-fef4930a-ecf6-4498-b6f0-6b7f0bb55377.png)

## Send a Message or Embed (not both) when someone joins.

## Variables you can use in Message.Message & Embed(title, author & description) & ImageText.Text:

|Variable|Replacement|
|--------|-----------|
|{user.id}|Will be replaced with the user id.|
|{user.name}|Will be replaced with the user name.|
|{user.discriminator}|Will be replaced with the users discriminator.|
|{guild.name}|Will be replaced with the guild name.|
|{guild.id}|Will be replaced with the guild id.|
|{guild.member_count}|Will be replaced with the guild member count.|


## Message

![image](https://user-images.githubusercontent.com/55946112/163334182-73bbd09f-4752-4ac4-8c5a-f183839c1d64.png)
 

If Message.Channel is not empty, the bot will send a message in this channel whena user joins.

Channel: This will be the ChannelId where the message should be sent when a user joins. Leave empty for no message.

Message: This will be the string that will be send when a user joins.

Reactions: ```unicode or emoji id``` ```Seperate with comma. Ex("😄,😎,5125125512512551")``` The bot will react to this message with these emojis.


## Embed 

![image](https://user-images.githubusercontent.com/55946112/163334581-b34cb990-ab78-44b4-8f92-90ed68768c91.png)


If Embed.Channel is not empty, the bot will send a embed in this channel when a user joins.

Channel: This will be the channelId where the embed will be sent when a user joins. Leave empty for no embed.

message: This will be the message content. Leave this empty for no message.

reactions: ```unicode or emoji id``` ```Seperate with comma. Ex("😄,😎,17236156511551")``` The bot will react to this embed with these emojis. 

timestamp: ```true or false``` Will display the time when the message was sent.

|Part|Variable|Replacement|
|----|--------|-----------|
|Thumbnail & Image|{user.avatar_url}|This will be replaced by the avatar url from the user.|
|Thumbnail & Image|{guild.icon}|This will be replaced by the guild icon url.|

Everything else should be self explainatory.


## Image

![image](https://user-images.githubusercontent.com/55946112/163335352-055d3328-7975-4c3a-a26c-1f6948f634d3.png)


This category contains information about the image.

ImageName: Here you have to put an picture file name that is inside of /BotFiles/mods/WelcomeImage

Widgth: This will be the width of the generated image. 750 is recommended.

Height: This will be the height of the generated image. 250 is recommended.

AvatarShape: ```Circle or any for Square``` This will be the shape of the avatar showing in the generated picture.

## ImageText

You can add up to 3 ImageTexts (name them upcounting ImageText1, ImageText2, ImageText3)

Text: This string will show at the image when someone joins.

Size: ```auto or number``` This will be the size of the text. Auto makes the text fit the pictrue.

## Check above for the variables you can use in ImageText.Text
