---
layout: post
title:  "Introducing WebEditor v2: Better, Faster and AsciiDoc"
date:   2015-02-24 00:01:00
categories: releases
author: samypesse
---


<!-- more -->

![GitBook WebEditor screenshot]({{ site.url }}assets/2015-02-24-webeditor-v2.png)

## AsciiDoc Support

Just a few weeks ago, GitBook's 2.0.0 release introduced [AsciiDoc support](https://www.gitbook.com/blog/releases/version-2-0-0), we're proud to announce that new web-editor has beautiful AsciiDoc support !

![Screenshot of AsciiDoc preview]({{ site.url }}assets/2015-02-24-webeditor-asciidoc.png)

## Better Performance

We have moved a lot of computationally intensive tasks to workers, such as spellchecking and previewing, freeing up the main thread resulting in a more fluid and pleasant writing experience.

### New Dictionaries: French, Italian, Spannish and German

GitBook's authors form a global community, with writers from all continents, Asia, Europe, ..., to offer a better experience to those international authors we're extending our spellcheck support. Support for french, italian, spanish and german is now built-in.

### Easy access to history

One of the great advantages of using Git, is that you never have to worry about losing your work or changes, everything is logged into your history. The editor now provides a quick and convenient means to access the history, useful for checking out your collaborators recent changes or recovering content.

![Screenshot of webeditor history]({{ site.url }}assets/2015-02-24-webeditor-history.png)

### Other improvements

This version includes many smaller improvements and bugfixes, such as: Drag and drop to upload or insert images, etc...
