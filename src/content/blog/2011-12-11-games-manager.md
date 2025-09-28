---
author: Sam
pubDatetime: 2011-12-11
title: Games Manager
slug: games-manager
featured: false
draft: false
tags:
  - old-wordpress-import
description: I had a bit of spare time today so i decided i would work on some more of the back end control for xBonxcom
---

I had a bit of spare time today so i decided i would work on some more of the back end control for xBonx.com.

Games are added automatically. When the system adds a users log it checks to see if the game they are playing is in the database. If the game is not it is added.
![Game Manager](http://cl.ly/0j3s0g1r0h2S3v36290F/Image%202011-12-11%20at%207.20.08%20PM.png)

The system will then send an email to a xBonx admin member who will be able to review a game the added game and add more information like game image and descriptions and anything else that applys. Other than doing this in the PHP MyAdmin there was no other way you could edit a game.

So i decided id make a quick way to manage games and edit there details in the admin section of the website.

It was really simple to do and has worked quite nice. Using the same ammended code as i wrote for the award manager i came up with something like this.
![Game Manager](http://cl.ly/1t3a0X02432Q2G3A2S0u/Image%202011-12-11%20at%205.19.50%20PM.png)

This will tell me what new games have been added and if they need reviewing or extra details adding.

I want to make it (In the near future) get the information it needs automatically at the time the game is added using an xbox RSS or API but for the mean time, this does the job nicely.