---
date: 2018-09-25
title: Why is Denied not skipping this disliked track?
categories:
  - Denied
description: "A bug prevents the disliked property from triggering properly if the album does not have artwork."
type: Document
---
Does the album or track you've disliked have its artwork set? The way Denied currently works is that it needs a few properties set before it registers as a song that can be checked by its properties. If the artwork  isn't set, Denied misses the 'disliked' flag.

I'm working on a fix, but you should be able to work around the issue by setting the album artwork manually:

1. Right click the album.
1. Select 'Album Info'.
1. If a dialog pops up, select 'Edit Items'.
1. Then select the 'Artwork' tab.
1. Press 'Add Artwork' and an image (any image will do).

Denied will now skip any disliked items on the album.
