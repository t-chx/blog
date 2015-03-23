---
layout: post
title:  "Editor: Proofreading & Spellcheck"
date:   2015-03-23 3:32:00
categories: features
author: samypesse
---

The editor is an essential part of the GitBook experience, authors need great tools to write their content. We've now integrated proofreading and spell checking directly into the editor, providing authors instant and valuable feedback as they type.

<!-- more -->

![Screenshot of the web-editor]({{ site.url }}assets/2015-03-23-proofreading.png)

### Proofreading

Proofreading helps avoid common mistakes by highlighting common errors such as wordy sentences, adverbs, passive voice, complicated words, etc ...

Proofreading is implemented with [Rousseau](https://github.com/GitbookIO/rousseau), a lightweight JavaScript library that we've [open sourced](https://github.com/GitbookIO/rousseau).

Rousseau only supports english for now, so feel free to contribute [on GitHub](https://github.com/GitbookIO/rousseau) to add support for your language !

### 30 new dictionaries

About 2 months ago, we introduced spellchecking with an initial 5 languages; this release is an upgrade brining 30 new dicitonaries including: Russian, Greek, Portuguese, ...

### Better Performance

This release is also much faster, it's quicker to load and seemlessly handles large documents.

### The future

This is just the beginning, proofreading is in it's infancy and we'll be working hard to continuously improve on it over the following months.
