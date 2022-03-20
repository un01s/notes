---
title: "Rebuild"
date: 2022-03-20T15:16:56-06:00
description: "how to build this hugo site"
tags: ["hugo"]
draft: false
---

```
$ brew install hugo -f yml
$ hugo version
hugo v0.94.2+extended darwin/arm64 BuildDate=unknown
$ hugo new site notes
$ cd notes
$ git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
$ echo "theme: \"PaperMod\"" >> config.yml
```
