---
date: 2018-05-06
title: Why does the music sometimes stutter?
categories:
  - Porthole 
description: Try optimizing your network settings.
type: Document
---
Streaming audio, especially in high quality, requires quite a lot of bandwidth. When you're streaming via Spotify, Rdio or any other app and add Porthole to the mix, that increases even more. If you experience stuttering in your music, the best thing you can do is maximize the performance of your network. The AirPort Express, for example, has an 802.11n-only or 5GHz mode, which increases the available bandwidth dramatically. Make sure other wireless devices support these modes before switching. We've also noticed that some network setups are more prone to dopped packages than others. Extending your network with an AirPort Express, for instance, might cause stuttering even while 802.11n and 5Ghz are enabled. Changing to setup according to the steps below should improve the situation:Connect your AirPort Express via an ethernet cable to the existing network;

On the Internet tab, under 'Connect Using' select 'DHCP';

On the Wireless tab, set the AirPort Express to create a new wireless network;

On the Network tab, set the network mode to 'Off (bridge mode)'.

The disadvantage is that you need to be able to connect your AirPort Express via a cable.. The advantage is obviously that you get rid of dropped packages and stuttering, but you can also setup two separate access points (one for older devices via 2.4Ghz 802.11b/g, one for newer device via 802.11n and 5Ghz).

Devices connected to either network can communicate with each other and can stream to the AirPort Express.

