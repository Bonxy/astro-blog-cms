---
author: Sam
pubDatetime: 2011-11-30
title: Whats been added up to now
slug: whats-been-added-up-to-now
featured: false
draft: false
tags:
  - old-wordpress-import
description: Since the last post which can be found here i have piled a few more features into the Xbox achievements...
---

Since the last post which can be found [here](http://bonxy.info/2011/11/19/a-different-type-of-xbox-achievements/) i have piled a few more features into the Xbox achievements.

Firstly, with some help off [@Cadab](http://imjam.es), i managed to sort out a neat little feature using what is normally a 404 error page.

This meant that i could create whatever i wanted to go after the foward slash and use it to detect different things.

So when you get a link like this: **[http://x.bonxy.net/Ghg8sj](http://x.bonxy.net/Ghg8sj)** the script will break it down.

The first letter after the forward slash is the 'type'. For instance, **G** means **Game**. So upon clicking this link you will get something like the below page.
![](http://cl.ly/2h1Z3S3607271g0Z1R0i/Image%202011-11-30%20at%209.17.47%20PM.png)

Other links that will look like the above, but they are infact all different will be;
- [**http://x.bonxy.net/LGMo0R**](http://x.bonxy.net/LGMo0R) - As this one starts with an **L** it means its a **Log** entry. IE, The system has logged someone playing a game.

- [**http://x.bonxy.net/AwnhHQ**](http://x.bonxy.net/AwnhHQ) - This one starts with an **A** which means it will link to an **Achievement**. IE, *BobTheBuilder* has unlocked this *something*.

You can also view a persons profile page by just going to the same above URL ([http://x.bonxy.net/](http://x.bonxy.net/)) and after the forward slash type a persons xbox live gamertag.

**Kings Reigns**

Like said in my first post about this project, this was going to be like a *foursquare* but for your xBox. So, one of the famous things about foursquare is mayorships. When you check into a place so many times, you become the mayor. Then you battle with other users to have the more check-ins of that place. If someone checks in more than you, you will lose the mayorship.

I have tried to import this system directly into xbox achievements. I want to make it so the more a user plays a game, the higher there count goes. (I have limited it this so it only counts 1 log per day per play. We dont want users cheating by turning on and off there xbox and make the logs get higher.)

![](http://cl.ly/2K3F1A410M44393G281D/Image%202011-11-30%20at%209.39.56%20PM.png)

A user has to have played the game a minimum of 3 non consecutive days before they become King. *(I didnt want to take Mayor's and mayorships so i changed it slightly.)* The more a user plays the game, when there king, the longer there reign will get. Another user can only get hold of the reign by beating the amount of plays by 1.

Once the new user has aquired the reign the system will tweet the new king, and the previous king the news.

![](http://cl.ly/3E2J3S0P102x1q3e3c35/Image%202011-11-30%20at%209.41.10%20PM.png)

The system seems to be working well at the moment, with already **12** reigns issued out of **23** games.

**Other People Playing**

Another really simple, but effective feature i quickly added was the chance to see which other users are playing the same game as you. When you click on a games itself, for instance *[Battlefield 3](http://x.bonxy.net/Glsle5)* you can see at the below what i am talking about.

![](http://cl.ly/3E2J3S0P102x1q3e3c35/Image%202011-11-30%20at%209.41.10%20PM.png)

**Future Plans**

This weekend i am hopefully going to be incorporating more features into the system. Im going to be changing the way logs and game counts are added to the database, im also going to hopefully integrate a points system, giving points for more consecutive days and other mini challenges that will be available through the site.

More news will be posted soon.