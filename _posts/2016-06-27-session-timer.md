---
layout: post
title:  "Session Timers"
date:   2016-06-27 10:30:00 +0900
categories: builderscon
author: lestrrat
---

Time keeping during a session is one of the main responsibilities of a conference staff. It's a simple enough job, but there are subtle things that must be taught to new staff members each time we hold a conference.

For example:
* At what times do you notify the speaker? 10 minutes left? 5 minutes left?
* Should you notify the speaker at different times if the session is shorter/longer?
* Should you share your timer with the speaker so they can see it?

So naturally we decided to build our own session timers :D

![](/assets/images/2016-06/web-timer.png)

As of today, we have a [simple web based timer](http://web.timer.builderscon.io) that you can use for time keeping 5, 15, 30, and 60 minute talks. The UI will notify you when you reach certain times (for 60 minute talks, this would be at T-15, 10, 5 minutes, and varies depending on the total time of the session). The web UI is intended to be displayed in a notebook or a tablet so that it can be shared with the speaker or the entire room.

![](/assets/images/2016-06/web-timer-ipad.jpeg)

We are also working towards releasing iOS and Android versions. These are meant to be used by the staff when you do not have the luxury of a big display. Provided we have enough resources, we also would like to make it possible to sync the displays so everyone is watching the same time.

In the same spirit as the conference itself, these tools are free, and you are welcome to use it in your meetups or conferences. Just make sure that you do not remove our name from them ... :)

The source code can be found in [Github](https://github.com/builderscon/session-timer), and we welcome anybody to help add more functionalities.

Hope this is uself. Keep on building!