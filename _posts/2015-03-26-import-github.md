---
layout: post
title:  "Import your GitHub/Git repository"
date:   2015-03-26 3:32:00
categories: features
author: samypesse
---

GitHub Integration is one of the key features of GitBook, we are now making easier to start out a book from a GitHub repository.

<!-- more -->

![Import using GitHub]({{ site.url }}assets/2015-03-26-import-github.png)

GitHub is an amazing product, with an amazing open source community; hosting your book source on it is a great way to get contribution from readers.

With this new feature, you can specify a GitHub repository when creating a book, it will be automatically cloned and setup to start new builds on GitBook everytime you commit.

You can also use a GIT repository url, for example to import from BitBucket or Assembla. Authentication, if needed, should be provided in the **https** url, eg: `https://user:password@myserver.com/repo.git`.
