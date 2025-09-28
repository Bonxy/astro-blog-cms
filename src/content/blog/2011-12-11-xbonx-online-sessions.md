---
author: Sam
pubDatetime: 2011-12-11
title: xBonx Online Sessions
slug: xbonx-online-sessions
featured: false
draft: false
tags:
  - old-wordpress-import
description: Ive been playing with xBonx quite a bit today thinking of and adding some new features to the service
---

Ive been playing with **xBonx** quite a bit today thinking of and adding some new features to the service.

Today i have finished off adding some logic that is going to start timing a user online sessions.

I already have some logic that updates a users profile to see if there *online* or *offline* and then posts it on there profile. 

So i implemented logic to log into a table when a user comes online and then it wont update the end time until the user turns there xbox off.
![](http://cl.ly/1h0J3u2G2O2v2m2k0W2j/Image%202011-12-11%20at%2011.30.02%20PM.png)

Now i have got the logic recording the time some starts playing a game and the time someone finishes i can write some logic to work out the time the user has been online and hopefully sort it into *online times per day* and then make some nice graphs and charts.

The whole idea behind **xBonx** was to collect and create the most stats we can for user and ther xbox.

More ideas will be coming soon.