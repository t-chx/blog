---
layout: post
title:  "Handling conflicts when merging branches or collaborating on a file"
date:   2016-02-29 10:00:00
categories: features
author: soreine
---

Stuck editing a book because of the infamous ['Can not fast forward'](https://github.com/GitbookIO/gitbook/issues/1117) error ? Fortunately, this should never happen again.

<!-- more -->

# Collaborate more, without problem

The version 5 of the editor will make collaboration on books even more seamless.
The new conflict resolution feature let several authors edit the same file at the same time, without encountering errors because of conflicts. Likewise, this feature allows merging of any branches, even if they have conflicting differences.

# Conflicts happen

Because GitBook allows authors to collaborate on a book, and keeps at
the same time an history of all changes, it sometimes has to deal with
changes on a same piece of text, made by different authors. This can happen when trying to merge two conflicting branches, or when several authors edit a branch at the same time. So far, this would result in [an error](https://github.com/GitbookIO/gitbook/issues/1117) and you were left stuck. Now you are given a way to handle these conflicts.

# Resolving conflicts

When conflicts happen, you are brought to a screen that let you
compare the two versions of a file, review and resolve the conflicts
between them, and submit a final version. The process is the same
whether you are merging two conflicting branches, or you and another
author made simultaneous changes.

There's just 3 steps to follow:

## Viewing conflicts

The list of conflicts you need to resolve is listed in the sidebar.

![Conflict list screenshot]()

## Resolving a conflict

When selecting a conflict, the center pane displays both versions of the file side-by-side.
You can edit the left side until you are satisfied with the final merged version. Once you are done, just __mark the conflict as solved__.

![Marked as solved screenshot]()

## Finalizing

Once all the conflicts have been solved, you can hit the __Apply__ button to commit the final merged version of the files.

# Future enhancements

Most of the time, GitBook should be able to merge automatically changes from both parties. When it can't, however, you are handed the raw list of conflicts. We aim to improve that by providing more meaningful conflicts and partially solve them for you when possible.

This new feature is the result of the adding conflict calculation capabilities to the open-source tool [repofs](https://github.com/GitbookIO/repofs). So we are working on improving these capabilities soon.
