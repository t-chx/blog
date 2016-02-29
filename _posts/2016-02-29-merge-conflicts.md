---
layout: post
title:  "Handling conflicts when collaborating on a book"
date:   2016-02-29 10:00:00
categories: features
author: soreine
---

Intense collaboration and merging branches just got easier!

<!-- more -->

# Collaborate more, without problem

Version 5 of the editor will make collaboration on books even more seamless. The new conflict resolution feature let several authors edit the same file at the same time, without encountering errors because of conflicts. Likewise, this feature allows merging any branches, even if they have conflicting changes.

# Conflicts happen

Because GitBook allows authors to collaborate on a book, and keeps at the same time an history of all changes, it sometimes has to deal with changes on a same piece of text, made by different authors. This can happen when trying to merge two conflicting branches, or when several authors are editing a branch at the same time. So far, this would result in [an error](https://github.com/GitbookIO/gitbook/issues/1117) and you were left stuck. From now on, you are given a way to handle these conflicts.

# Resolving conflicts

When conflicts happen, you are brought to a screen that let you compare both versions of a file, review and resolve any conflict between them, and submit a final version. The process is the same whether you are merging conflicting branches, or you and another author made simultaneous changes.

There's just 3 steps to follow:

## Viewing conflicts

The list of conflicts you need to resolve is listed in the sidebar.

![Conflict list screenshot]({{ site.url }}assets/2016-02-29-conflict-list.png)

## Resolving a conflict

When selecting a conflict, the center pane displays both versions of the file side-by-side.

![Review a conflict screenshot]({{ site.url }}assets/2016-02-29-review-conflict.png)

You can edit the left side until you are satisfied with the final merged version. Once you are done, just __mark the conflict as solved__.

![Marked as solved screenshot]({{ site.url }}assets/2016-02-29-mark-as-solved.png)

## Finalizing

Once all the conflicts have been solved, you can hit the __Apply__ button to commit the final merged version and go back to your writing.

# Future enhancements

Most of the time, GitBook should be able to merge automatically changes from both parties. When it can't, however, you are handed the raw list of conflicts. We aim to improve that by providing more meaningful conflicts and partially solve them for you when possible. For now, avoiding to be stuck on conflicts was the top priority.

This new feature is the result of adding new conflict calculation capabilities to the open-source library [repofs](https://github.com/GitbookIO/repofs). Hence we will continue to improve these capabilities.
