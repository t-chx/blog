---
layout: post
title:  "Editor: Conflict resolution UI"
date:   2016-03-02 10:00:00
categories: features
author: soreine
---

Merge conflicts are now a little less scary, thanks to our new Editor !

<!-- more -->

[![Merge with conflicts UI]({{ site.url }}assets/2016-03-02-conflicts.jpg)]({{ site.url }}assets/2016-03-02-conflicts.jpg)

### What are conflicts ?

Conflicts happen when two people edit the same part of a page/document at the same time on different computers. GitBook can typically merge changes back together, but sometimes it's too ambiguous for GitBook to decide by itself and needs your help.

### Resolving conflicts

Technical users can resolve conflicts using the command line, but that's not very user friendly.

Now GitBook automatically detects when a conflict will happen and displays the conflict resolution UI, allowing you to simply resolve any conflicts in a few clicks.

Our editor is now one of the first tools that allows you to graphically solve merge conflicts, providing a faster and smoother user experience. Previous editor versions and most other GUI software (e.g: GitHub Desktop) throw [errors](https://github.com/GitbookIO/gitbook/issues/1117) when encountering conflicts.

![Review a conflict screenshot]({{ site.url }}assets/2016-03-02-review-conflict.png)

### Future enhancements

The main goal of this feature was to prevent conflicts from blocking non-technical users. Moving forward, we'll make our conflict resolver smarter, so that it can do most of the work and when it can't make it more user friendly.

If you're interested in the technical details:
This feature was made possible by adding new conflict calculation capabilities to our open-source library: [GitbookIO/repofs](https://github.com/GitbookIO/repofs). Feel free to take a look and even send a PR !

Thanks for your continued feedback and support ! Let us know what you would like to see improved in the next release !
