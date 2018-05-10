---
date: 2018-05-06
title: Why don't I hear anything when I start streaming?
categories:
  - Porthole 
description: Make sure you're running the latest version.
type: Document
---
Porthole v1.4.5. changes some AirPlay protocol related things that could fix this problem. Make sure you're running the latest version by updating in-app or [downloading the latest version](https://www.dangercove.com/porthole/download).

The volume Porthole sends to the AirPlay device is hooked up to your system volume, so make sure it's set at an appropriate level:

First start Porthole, connect to your AirPlay device and play a song.

Now use the volume keys on your keyboard to make sure the volume is maxed out. Also go into Porthole's preferences, then go to the Volume panel and make sure all speakers are set to 0 or higher.

If that didn't change anything, open System Preferences (/Applications/System Preferences.app), then go into Sound and make sure the volume slider for Soundflower (2ch) on both the Input and Output tab is maxed out. Normally you should be able to see the Input Level indicator respond to audio playing.

If there's still no output and the problem started spontaneously, try rebooting your Mac and leave Porthole streaming for a while (15 minutes or more) before trying the other solutions. In most cases the sound comes back after a few minutes.

Some speakers enter a sleep state when they're turned on, but no audio is being played during a period of time. It might take a moment for the speakers to "wake up" after you start streaming. Repeatedly changing the volume during this period ensures there's audio being sent to the output devices.

A few apps sometimes don't register when Porthole changes the audio device and keep playing over the built-in speakers while Porthole's streaming. If this happens, completely quit the app, start streaming with Porthole and start the app again. The audio should now play over AirPlay. If you're using a web based music server, try a different browser to see if the problem persists.

If the above didn't work, [try reinstalling Soundflower](/porthole/how-do-i-uninstall-or-reinstall-soundflower).
