---
date: 2019-02-13
title: Why isn't my custom theme working?
categories:
  - Carbonize
description: "A limitation of the underlying web engine prevents the custom theme from being used."
type: Document
---

[Carbon.now.sh](https://carbon.now.sh) uses two distinct ways to generate an image from code. On Chrome it uses the browser itself. For Safari (which is what Carbonize uses) the image gets generated on a server through an API call. It seems the custom theme feature has not been implemented yet on the backend. This means it won't work in Carbonize.

While developing Carbonize I was on the fence about either hiding these types of (currently) unsupported features, or leaving them in. I chose to leave them in for now, so that if these option do get implemented, Carbonize would be ready instantly without me having to release an update.
