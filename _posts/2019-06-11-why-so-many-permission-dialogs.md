---
date: 2019-06-11
title: Why so many permission dialogs?
categories:
  - Pipvid 
description: Pipvid needs to control VLC and QuickTime and asks your permission to do so.
type: Document
---

Pipvid controls both QuickTime and VLC and through various methods. Primarily it uses the Accessibility features of macOS. The app specifically asks you to grant permission to do so after the app first launches.

![Dialog asking for Accessibility permission for Pipvid](/images/screenshots/pipvid-permission.png)

Besides that there are a few Apple Events that Pipvid utilizes to go through menus of VLC and QuickTime, to enable Float on Top.

![Dialog asking for System Events permission for Pipvid](/images/screenshots/pipvid-system-events.png)

Finally it asks for permission to control the Dock so it can enable VLC and QuickTime to appear on all Desktops.

## Revoking permission

If at any time you want to revoke permission for any of these features. You can go into System Preferences &rarr; Security & Privacy &rarr; Privacy and then either Accessibility or Automation to revoke any of the granted privileges.

![Dialog showing permissions can be revoked](/images/screenshots/pipvid-revoke.png)
