---
author: Sam
pubDatetime: 2023-01-06
title: Learning To Make An App
slug: learning-to-make-an-app
featured: false
draft: false
tags:
  - old-wordpress-fixed
  - making-an-app
  - developer
  - app-development
description: So having always had an interest in coding and building websites
  etc Ive decided in 2023 that im going to try and build a native iOS app from
  scratch in xcode...
---
So, having always had an interest in coding and building websites etc I've decided in 2023 that i'm going to try and build a native iOS app from scratch in xcode.

I'm hoping i can keep track of my progress in this blog and hopefully in the next couple of months have a functioning app that does what i need it to do.

The Idea

Since ive always had an interest in fitness related apps and website and tracking them stats, a simple step leaderboard seems the perfect place to start.

I want to keep it simple.

*   App opens into a splash screen asking for permissions.
    
*   Once permissions are granted, it opens straight onto the leaderboard.
    
*   A simple menu with a button that allows you to add a friend via an email address.
    
*   Another button in the menu to delete your data.
    

The data will be held and managed on a server. The app syncs step data and the server returns an api with leaderboard data that the app can display.

Identifiers will be used to tie data to users who can in turn attach an email address to add friends. You type an email address and that sends the friend an email (push notifications would be nice?), they accept/decline through the email which then sends them back to the app.

This is the simplest way i'm thinking of going with. Things may change over time. Who knows were this project might end up.