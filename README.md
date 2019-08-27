![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)![TK Logo](/logo.png)
# TKMedia Documentation ([BUY/UPDATE](https://store.sansar.com/listings/1b1274e3-0f40-45f4-8d82-325d1a1c5235/tikimedia))
This script is used to override your media source in the experience. The thing that makes this script different from other scripts available in market is that you can create multiple __[CHANNELS]__ so people in different channels can watch different videos. Same concept as watching different videos in different rooms of a building.

>- current version: 1.3
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
/tkey help | tkey commands list | /tkey help
/tkey [channelNumber] [PASSWORD] | sets new password for a channel | /tkey 3 a23das2
/tkey [channelNumber] off | removes channel's password | tkey 3 off

_Attention:_
>- Don't use `space` in your [PASSWORD].
>- You can't set any [PASSWORD] for channels __`0`__ and __`1`__.

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
