---
title: 'Rakun.js devlog #1'
tags: [rakunjs, devlog, programming, javascript, frameworks]
date: 2016/12/28
---

Rakun.js is a un-opinionated, javascript plugin for wide usage.
Currently in beta stage, it is used in couple projects, such as [itm.biz.pl](http://itm.biz.pl) internal android mobile application or as a Single Page Application framework for [inku.js](https://github.com/lukaszkups/inku). 

## The idea behind Rakun.js creation

Rakun.js is developed with zero-dependency approach and can be used with existing tools, e.g. with [axios](https://github.com/mzabriskie/axios) or [jQuery](http://jquery.com) plugins.
The main reason behind Rakun.js creation is tiredness of disease, most commonly known as javascript fatigue.

Nowadays developers tend to complain about rapid development of popular tools and approaches of using them.

I was one of them.

But I decided to free ourself from this trend by creating [Rakun.js](https://github.com/lukaszkups/rakun.js).
I'm into web development since I've learned about what is HTML and when using `<table><table>` was the only right approach of creating websites.

Then SPA happened.

Interactive websites became a monsters, called "Single Page Applications" - from the one side it was very clever way of building webpages: e.g. unification of structuring many javascript files and spreading functionalities between them - that's a good thing. 

But tools became more and more powerful, what led to its overcomplication. Task runners which were at first an optional automation helpers has transformed to necessary components of SPAs. There's even a meme about random programmer who - after spending a whole weekend configuring webpack - is ready to start programming his side project. 

We have new abstraction layers, such as Virtual DOM (I'm waiting for another abstraction layer for it trolololo :D ) - don't get me wrong - it's a good thing that people are making new, awesome tools, but most of programmers just *follow the hype* and use them everywhere they can (even they shouldn't).

Personally, I was really tired/frustrated/You-name-it of constantly keeping up to date with another shiny react-like-but-smaller/better/more-awesome lib.
I had a constant feeling that I'm not up-to-date with my technologic field of expertise, that I'm behind other devs.

Finally I've decided to just *fuck that* and I've created a tool that will help me build stuff like I've used and loved to - without generating tons of HTML code in javascript files using weird HTML-ish syntax (to be honest I remember times when generating whole apps with js was an anti-pattern - for me, even if I'm aware of pros and cons about this it feels just unnatural).

In the following devlogs I'll present the way how Rakun.js works and some basic usage tips.

And how's about You? Do You follow the hype?

Best,

-- ł.
