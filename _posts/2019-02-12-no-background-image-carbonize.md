---
date: 2019-02-12
title: Why isn't the background image included?
categories:
  - Carbonize
description: "Upgrade to Carbonize v1.1 to fix this issue."
type: Document
---

Download and install [Carbonize v1.1 from the Mac App Store](https://www.dangercove.com/carbonize/appstore) to fix this issue and enable instant exports.

~~Carbonize relies on `WKWebView` (which is basically Safari) to perform all the web related tasks for Carbonize. There's a limitation on how much information it can send to the server that renders the stylized code images. Adding a background image currently crosses that limit.~~
