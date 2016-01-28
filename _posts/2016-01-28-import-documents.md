---
layout: post
title:  "Import Word and Docbook documents"
date:   2016-01-28 10:00:00
categories: features
author: jpreynat
---

Migrating from Microsoft Word or Docbook to GitBook.com has never been that easy !

<!-- more -->

Starting today, importing your existing documents on GitBook.com is as simple as creating a new book.

![Import at creation]({{ site.url }}assets/2016-01-28-import-new-book.png)

### Word and Docbook

The import feature has been incorporated directly in the book's creation form: select your document in the "Import" tab, and you're ready to go!

If you already created your book, documents can also be imported into empty books using the `Import a document` button.

More informations about the import process are detailled in the [GitBook's documentation](https://help.gitbook.com/format/index.html).

### Open source CLI

This feature is using, behind the scenes, a new open source CLI tool: [gitbook-convert](https://github.com/GitbookIO/gitbook-convert).

**gitbook-convert** has been built to easily convert all types of documents to the GitBook format. Based on your original document's structure, it generates the corresponding Markdown files, and the Table of Contents.

As always, feel free to [contribute and tell us](https://github.com/GitbookIO/gitbook-convert) what format you are hoping to see supported.
