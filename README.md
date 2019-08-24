# TKMedia Documentation ![GitHub Logo](https://avatars1.githubusercontent.com/u/26417952?s=100)
This script is used to override your media source in the experience. The thing that makes this script different from other scripts available in market is that you can create multiple __[CHANNELS]__ so people in different channels can watch different videos. Same concept as watching different videos in different rooms of a building.


## Commands
There are two kind of commands for this script

- [__User Commands__](#user-commands-list)
  - commands used to join __[CHANNELS]__
  - commands used to open videos and web pages
- [__Moderator Commands__](#moderator-commands-list)
  - commands used to manage __[CHANNELS]__
  - commands used to manage __[PASSWORDS]__
  - commands used to manage __[BANNED]__ users



### USER Commands list
###### Commands used to join [CHANNELS]

Command | help | Example
:--- | :--- | :--- 
/tch help | tch commands list | /tch help
/tch | shows all available channels | /tch
/tch [channelNumber] |  to join a specific channel  | /tch 3

_Attention:_

>If your current channel is PRIVATE, you can't use any video commands without knowing channel's __[PASSWORD]__.
You have to write this __[PASSWORD]__ before your video links. Example:
>/tk 1234a2esa [https://www.youtube.com/watch?v=fajgHyPHmV4]()


###### Commands used to open videos and web pages

Command | Optional | help | Example
:--- | :--- | :--- | :---
/tk help | | tk commands list | /tk help
/tk [video link] | [params] | plays your video link | /tk [https://www.youtube.com/watch?v=fajgHyPHmV4]() loop
/url [webpage link] |  | opens a web page | /url [https://www.google.com]()


### MODERATOR Commands list
###### commands used to manage __[CHANNELS]__
Command | help | Example
:--- | :--- | :---
/tch help | tch commands list | /tch help
/tch open [channelName] [PASSWORD] | adds a new channel | /tch open room3 as23ad2
/tch close [channelNumber] | removes a channel | /tch close 3

_Attention:_
>- Don't use `space` in your [channelName] or [PASSWORD].
>- Setting [PASSWORD] is optional.
>- You can't remove channels __`0`__ and __`1`__.

###### commands used to manage __[PASSWORDS]__
Command | help | Example
:--- | :--- | :---
/tkey help | tkey commands list | /tkey help
/tkey [channelNumber] [PASSWORD] | sets new password for a channel | /tkey 3 a23das2
/tkey [channelNumber] off | removes a channel's password | tkey 3 off

_Attention:_
>- Don't use `space` in your [PASSWORD].
>- You can't set any [PASSWORD] for channels __`0`__ and __`1`__.

###### commands used to manage __[BANNED]__ users
Command | help | Example
:--- | :--- | :---
/tban help | tban commands list | /tban help



