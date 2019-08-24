# TKMedia Documentation ![GitHub Logo](https://avatars1.githubusercontent.com/u/26417952?s=100)
This script is used to override your media source in the experience. The thing that makes this script different from other scripts available in market is that you can create multiple __[CHANNELS]__ so people in different channels can watch different videos. Same concept as watching different videos in different rooms of a building.


### Commands
There are two kind of commands for this script

- [__User Commands__](#user-commands-list)
  - commands used to join __[CHANNELS]__
  - commands used to open videos and web pages
- [__Moderator Commands__](#moderator-commands-list)
  - commands used to manage __[CHANNELS]__
  - commands used to manage channel __[PASSWORDS]__
  - commands used to manage __[BANNED]__ users



#### USER Commands list
* Commands used to join [CHANNELS]

Command | help | Example
:--- | :--- | :--- 
/tch help | commands list | /tch help
/tch | shows all available channels | /tch
/tch [channel number] |  to join a specific channel  | /tch 3

__Attention:__

>If your current channel is PRIVATE, you can't use any video commands without knowing channel's __[PASSWORD]__.
You have to write this __[PASSWORD]__ before your video links. Example:
>/tk 1234a2esa [https://www.youtube.com/watch?v=fajgHyPHmV4]()


* Commands used to open videos and web pages

Command | Optional | help | Example
:--- | :--- | :--- | :---
/tk help | | commands list | /tk help
/tk [video link] | [params] | plays your video link | /tk [https://www.youtube.com/watch?v=fajgHyPHmV4]() loop
/url [webpage link] |  | opens a web page | /url [https://www.google.com]()

__Attention:__

>__[params]__
>- youtube:
>   - __`loop`__ to repeat playing same video (if it's not part of a playlist).

#### MODERATOR Commands list
