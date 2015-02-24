---
layout: post
title:  "Improvement on the WebEditor: Faster, Stable, AsciiDoc"
date:   2015-02-24 00:01:00
categories: releases
author: samypesse
---


<!-- more -->

![GitBook WebEditor screenshot]({{ site.url }}assets/2015-02-24-webeditor-v2.png)

## AsciiDoc Support

Since GitBook 2.0.0 brings [support to AsciiDoc](https://www.gitbook.com/blog/releases/version-2-0-0), this new web-editor is supporting parsing and previewing book written using AsciiDoc.

![Screenshot of AsciiDoc preview]({{ site.url }}assets/2015-02-24-webeditor-asciidoc.png)

## Performance Improved

Performance of the editor was a crucial point we wanted to improve, in this version the previewing and spellchecking is done in background worker to improve the fuilidity of the application.

### New Dictionaries: French, Italian, Spannish and German

This version brings support for more languages in spellchecker. You can select the dictionary in the editor settings.

### Easy access to history

When writing, it's always usefull to be able to quickly acecss the history of your modifications. This is now possible using the "History" feature in the web editor that gives you a quick and simple oversee of the book history.

![Screenshot of webeditor history]({{ site.url }}assets/2015-02-24-webeditor-history.png)

### Other improvements

This new version includes a certain number of small but usefull improvements such as: Drag and drop to upload or insert images, etc.
