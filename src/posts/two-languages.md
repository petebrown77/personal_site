---
title: There are two types of programming languages
desc: or why I hate Java
date: 2022-09-29
draft: true
tags:
  - experience
  - dev-life
layout: post.layout.njk
---

The way I see it, there are two types of programming languages: 

### Dev Slow, Run Fast (DSRF)
This category consists of the slow to write languages, like C++, Rust, C, assembly, etc.  These languages are tedious to write, having to deal with pointers
and whatnot.  However, you write in these languages when you need the speed that they have, like writing operating systems or running trading infrastruture.
So even when you're chasing down a random segfault, you do so knowing that when this code runs, it'll run fast enough for whatever you need it to do.
### Dev Fast, Run Slow (DVRS).
On the other side, you have the languages like Python, Ruby, Javascript, etc. which are really slow to run, but incredibly fast to build a project with. With these languages,
creation is really fast, with people being able to stand up a website in just a weekend.

### What does this have to do with Java?
So, I think Java sits between the two of these languages, being too verbose to be quick to develop, but too slow to be performant critical.
