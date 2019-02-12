---
date: 2019-02-12
title: Why isn't the background image included?
categories:
  - Carbonize
description: "A limitation of the underlying web engine prevents the background image from being used.
type: Document
---

Carbonize relies on `WKWebView` (which is basically Safari) to perform all the web related tasks for Carbonize. There's a limitation on how much information it can send to the server that renders the stylized code images. Adding a background image currently crosses that limit.
