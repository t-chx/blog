---
layout: post
title:  "Builds: Default & whitelisted branches"
date:   2015-11-13 11:00:00
categories: features
author: jpreynat
---

GitBook now plays nicely with non-default branch setups !

<!-- more -->

### When do I need whitelisted branches ?

[Automatic builds]({{ site.url }}features/build-branches) are an essential part of the Gitbook workflow especially if you use our GitHub integration.

Often times when using GitBook to write your documentation, you'll store your docs in a `/docs/` subfolder of your repo alongside your code or other times in a branch named `docs` or `gitbook`.

In the latter case you'll want to whitelist or change your default branch to match up with the branch where your docs are stored so you don't trigger unecessary GitBook builds.

![Branches whitelist]({{ site.url }}assets/2015-11-11-branches-whitelist.png)

### Where can I change my default branch ?

By default all branches are whitelisted and your default branch is `master`, but you can easily change those now in a few clicks from your book's settings page.

Best of luck writing and branching ! :)
