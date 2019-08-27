![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)
# TKMedia Documentation ([BUY/UPDATE](https://store.sansar.com/listings/1b1274e3-0f40-45f4-8d82-325d1a1c5235/tikimedia))
TKMedia uses these 4 commands. {"/tk", "/tch", "/tpass", "/tban"}. the most important command that is used to open your media links is "/tk". this command will convert your links to embed links. E.g. your link is a youtube video there will be no adds and its going to be fullscreen. (ofc, you can use /url if you need to open webpages or... .) you will see this command and other following commands, introduced in details in next section. The thing that makes this script different from other scripts available in market is that you can create multiple __[CHANNELS]__ so people in different channels can watch different videos. Same concept as watching different videos in different rooms of a building and the command to use this feature is "/tch".

to prevent people from abusing your media script, there are two options you can use in your advantage. you can use "/tpass" to set password for your channels, so in a crowded experiance, only the few who knows the pass can use the commands. by using your other option,"/tban", you can ban few users who are abusing your script so they wont have access to commands anymore.

>- current version: 1.4
>- release date   : August 27 2019

## Commands
There are two kind of commands for this script. You can write __`/tiki`__ in your chatbox in Sansar to see all Commands.

- [__User Commands__](#user-commands-list)
  - [commands used to join __[CHANNELS]__](#commands-used-to-join-channels)
  - [commands used to open videos and web pages](#commands-used-to-open-videos-and-web-pages)
- [__Moderator Commands__](#moderator-commands-list)
  - [commands used to manage __[CHANNELS]__](#commands-used-to-manage-channels)
  - [commands used to manage __[PASSWORDS]__](#commands-used-to-manage-passwords)
  - [commands used to manage __[BANNED]__ users](#commands-used-to-manage-banned-users)



## USER Commands list
#### Commands used to join [CHANNELS]

Command | Help | Example
:--- | :--- | :--- 
/tch help | tch commands list | /tch help
/tch | shows all available channels | /tch
/tch [channelNumber] |  to join a specific channel  | /tch 3

_Attention:_

>If your current channel is PRIVATE, you can't use any video commands without knowing channel's __[PASSWORD]__.
You have to write this __[PASSWORD]__ before your video links. Example:
>/tk 1234a2esa [https://www.youtube.com/watch?v=fajgHyPHmV4]()


#### Commands used to open videos and web pages

Command | Optional | Help | Example
:--- | :--- | :--- | :---
/tk help | | tk commands list | /tk help
/tk [video link] | [params](#params) | plays your video link | /tk [https://www.youtube.com/watch?v=fajgHyPHmV4]() loop
/url [webpage link] |  | opens a web page | /url [https://www.google.com]()


## MODERATOR Commands list
#### Commands used to manage __[CHANNELS]__

Command | Help | Example
:--- | :--- | :---
/tch help | tch commands list | /tch help
/tch open [channelName] [PASSWORD] | adds a new channel | /tch open room3 as23ad2
/tch close [channelNumber] | removes a channel | /tch close 3

_Attention:_
>- Don't use `space` in your [channelName] or [PASSWORD].
>- Setting [PASSWORD] is optional.
>- You can't remove channels __`0`__ and __`1`__.

#### Commands used to manage __[PASSWORDS]__

Command | Help | Example
:--- | :--- | :---
/tpass help | tpass commands list | /tpass help
/tpass [channelNumber] [PASSWORD] | sets new password for a channel | /tpass 3 a23das2
/tpass [channelNumber] off | removes channel's password | /tpass 3 off

_Attention:_
>- Don't use `space` in your [PASSWORD].

#### Commands used to manage __[BANNED]__ users

Command | Help | Example
:--- | :--- | :---
/tban help | tban commands list | /tban help
/tban all | only Moderators and Owner can use commands | /tban all
/tban [user handle] | bans user from using commands | /tban tiki-8591
/tban off | removes all banned users | /tban off
/tban off [user handle] | removes banned user | /tban off tiki-8591

_Attention:_
>- [user handle] Example: username-9999
>- [user handle] is not caseSensitive.

## [[params]](#commands-used-to-open-videos-and-web-pages)
(Optional parameters used for video commands)

Source | Parameter | Help
:--- | :--- | :---
youtube | loop | to repeat playing same video.
youtube | list | to play videos in playlist.

## Logs

Version | Log 
:--- | :--- 
1.4 | "/tkey" -> "/tpass" and now owner will get debug (Ctrl + D) message for each media request.
1.3 | adding "/tban all" and the ability to set password for public channel
