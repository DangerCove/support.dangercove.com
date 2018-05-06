---
date: 2018-05-06
title: Why can't I connect to an Apple TV 4?
categories:
  - Porthole 
description: "Version 10.2 of the Apple TV 4th generation's firmware includes a change that prevents Porthole and other third-party apps to connect to it."
type: Document
---
Version 10.2 of the Apple TV 4th generation's firmware includes a change that prevents Porthole and other third-party apps to connect to it.

Unfortunately, I'm not aware of a workaround or fix for this issue. My recommendation is to not update to the latest version, and disable auto-updates on the Apple TV.

There are guides on the internet that describe ways to downgrade the Apple TV's firmware. This will restore the option to stream to it, but the process isn't trivial and unsupported by Apple. I can't recommend it.

If Porthole fails to connect to your Apple TV 4 and it displays the following notice: "This AirPlay connection requires iOS 7.1 or later; OS X 10.10 or later; or iTunes 11.2 or later." you'll need to disable Device Verification on your Apple TV.

Here's how that works:

1. Go to Settings > AirPlay.
1. Disable Device Verification.

Porthole should now work as expected.

