---
layout: release
title: Version 1.3.6 released
excerpt: Details of the 1.3.6 release
tags: [releases, 1.3.6]
categories:
    - releases
---
## Version 1.3.6

Mostly bug fixes with this release. The biggest change is that the editor now has much better iOS support.

A new function blur() has also been added which will remove focus from the editor.

### Full 1.3.6 changelog:
 * Added Spanish translation - Thanks to Maxpower for translating
 * Fixed YouTube command not matching youtu.be URLs
 * Added form reset support
 * Added autoExpand option
 * Fixed bug related to inserting BBCodes in source mode when textarea is empty. - Thanks to Martec for reporting
 * Fixed stripQuotes bug - Thanks to Maxpower for reporting
 * Fixed destory() to stop memory leak
 * iOS bug with content overflowing the container
 * Fixed font size BBCode bug with WebOS browser
 * Added blur() function
 * Fixed list bug where newlines from the end would be removed - Thanks to Birkoff Keren for reporting
 * Fixed whitespace removal bug causing some whitespace to be left. - Thanks to Martec for reporting
 * Fixed val() helper function bug returning HTML when in source mode. - Thanks to Maxpower for reporting
 * Fixed bug with IE compatibility modes "Quirks" and "IE 7" causing new lines not to show.
