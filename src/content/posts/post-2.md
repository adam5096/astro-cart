---
title: "GIT"
pubDate: 2024-09-01
description: "這是GIT的一些注意事項"
image:
  url: "https://docs.astro.build/default-og-image.png"
  alt: "The word astro against an illustration of planets and stars."
author: "Adam"
tags: [ "git", "rebase", "revert", "fetch", "push", "pull"]
---

git pull => git fetch + git rebase

rebase
+ 調整 commit 順序
+ 刪除指定 commit
+ 合併指定 commit
+  ...

revert
+ 撤回某次 commit, 使版本回到該 commit 前一版
+ ...