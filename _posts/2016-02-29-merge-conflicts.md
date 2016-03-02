---
layout: post
title:  "Resolve conflicts when collaborating on a book"
date:   2016-03-02 10:00:00
categories: features
author: soreine
---

Intense collaboration for large team and merging branches just got easier!

<!-- more -->

[![Merge with conflicts UI]({{ site.url }}assets/2016-03-02-conflicts.jpg)]({{ site.url }}assets/2016-03-02-conflicts.jpg)

### Collaborate more, without problem

The new version of the editor will make collaboration on books even more seamless. The new conflict resolution feature let several authors edit the same file at the same time, without encountering errors because of conflicts. Likewise, this feature allows merging any branches, even if they have conflicting changes.

### Conflicts happen

Because GitBook allows authors to collaborate on content, and keeps at the same time an history of all changes, it sometimes has to deal with changes on a same piece of text, made by different authors. This can happen when trying to merge two conflicting branches, or when several authors are editing one branch at the same time. So far, this would result in [an error](https://github.com/GitbookIO/gitbook/issues/1117) and you were left stuck. From now on, you are given a way to resolve these conflicts.

### Resolving conflicts

When conflicts happen, you are brought to a screen that let you compare both versions of a file, review and resolve any conflict between them, and submit a final version. The process is the same whether you are merging conflicting branches, or you and another author made simultaneous changes.

![Review a conflict screenshot]({{ site.url }}assets/2016-03-02-review-conflict.png)

### Future enhancements

Most of the time, GitBook should be able to merge automatically changes from both parties. When it can't, however, you are handed the raw list of conflicts. We aim to improve that by providing more meaningful conflicts and partially solve them for you when possible. For now, avoiding to be stuck on conflicts was the top priority.

This new feature is the result of adding new conflict calculation capabilities to the open-source library [repofs](https://github.com/GitbookIO/repofs). Hence we will continue to improve these capabilities.
