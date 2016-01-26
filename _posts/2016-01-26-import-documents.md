---
layout: post
title:  "Import existing documents"
date:   2016-01-26 10:00:00
categories: features
author: jpreynat
---

Migrating to GitBook.com has never been that easy !

<!-- more -->

Starting today, importing your existing documents on GitBook.com is as simple as creating a new book.

### Import at book creation

![Import at creation]({{ site.url }}assets/2016-01-26-import-new-book.png)

The new book form has been redesigned to incorporate this functionnality in the existing Import tab. Meanwhile, the *Import from git* feature has been transferred to its own new Git tab.

### Import using an empty book

The welcome page for your empty books now allows you to import a document as well.

![Import on an empty book]({{ site.url }}assets/2016-01-26-import-empty-book.png)

### Import process

Using the [gitbook-convert](https://github.com/GitbookIO/gitbook-convert) module, this new feature will automatically generate markdown files from your document, including the summary.

Based on your original document's structure, [gitbook-convert](https://github.com/GitbookIO/gitbook-convert) will create chapters and sub-chapters for each title.

Have a look at [GitBook's documentation](https://help.gitbook.com/format/index.html) for more informations about the import process.

We hope to hear from your suggestions about other formats that you would like to be supported on the next releases !
