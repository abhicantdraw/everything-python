---
toc: true
layout: post
description: How we can view our bash history a little more colorfully
categories: [commands. libraries]
title: history Revisited
---

One of my most used libraries in Unix is the `history` command. It's a major pet peeve of mine that the built-in command does not display the timestamp of commands used by default. As a result, the first thing I now do in every Linux distro/ WSL distro I install is add 

`HISTTIMEFORMAT='%F %T '` to the `~/.bashrc` file. Among other variables. But more on those later. 

The goal of this post is to make the bland history output look..rich-er.. with a little help from our friends....