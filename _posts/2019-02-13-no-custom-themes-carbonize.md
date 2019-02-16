---
date: 2019-02-13
title: Why isn't my custom theme working?
categories:
  - Carbonize
description: "Upgrade to Carbonize v1.1 to fix this issue."
type: Document
---

Download and install [Carbonize v1.1 from the Mac App Store](https://www.dangercove.com/carbonize/appstore) to fix this issue and enable instant exports.

~~[Carbon.now.sh](https://carbon.now.sh) uses two distinct ways to generate an image from code. On Chrome it uses the browser itself. For Safari (which is what Carbonize uses) the image gets generated on a server through an API call. It seems the custom theme feature has not been implemented yet on the backend. This means it won't work in Carbonize.~~

~~While developing Carbonize I was on the fence about either hiding these types of (currently) unsupported features, or leaving them in. I chose to leave them in for now, so that if these option do get implemented, Carbonize would be ready instantly without me having to release an update.~~
