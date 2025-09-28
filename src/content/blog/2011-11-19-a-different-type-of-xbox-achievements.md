---
author: Sam
pubDatetime: 2011-11-19
title: A different type of Xbox achievements
slug: a-different-type-of-xbox-achievements
featured: false
draft: false
tags:
  - old-wordpress-import
description: While spending a little time developing a twitter for xbox app last night which im sure Cadab will do a write up for soonish i came accross the idea of taking a...
---

While spending a little time developing a twitter for xbox app last night, which im sure @Cadab will do a write up for soonish, i came accross the idea of taking a users xbox details and awarding achievements. 

They would not be achievements like in-game achievements, nor would they offer you gamerscore. Its basically just for fun but will offer stats and information about your game play, games you have played, time spent on the xbox and so on. 

I started last night by doing the easiest thing and just adding the game you where playing to a database i created. This will then check (Using a Cron job) every 15 minutes to see if you are online. If you are online, the game you will be playing will be added. After the next 15 minutes, if your playing the same game, nothing will happen. Only 1 game play per day will be added to the database. If you have changed games, this new game will be added to the database. You will not be able to keep swapping between games to accumalate game plays. 

I then have another page wont runs a script more often. This is user to award user with there achievements. Im calculating achievements using logic to work out how long a user has been online for, or how many times they have played a certain game, how many consecutive days playing xbox live. I can use it to calculate the award which will then be 'added' to that users account on my site. 

I can make it harder for people to get awards by increasing different targets. Eg: I can set an award to be awarded after 30 consecutive days or playing, which will be hard, if they miss a day, there tally will be reset to zero and they will have to start again. 

Hopefully i can keep adding to it and make awards for totally different things IE; '*Playing the new Battlefield 3 within 24hours or release*' or '*1 Year Old - For playing a game over a whole year!*'.

Ill update this more when more work is carried out.