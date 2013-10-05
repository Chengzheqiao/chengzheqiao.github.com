---
layout: post
title: "I m the first"
description: ""
category: ""
tags: []
---
{% include JB/setup %}

我就是来看看怎么编辑，好不好用。
phantomjs is one of the two solutions I’m aware of that solves the headless browser problem. What makes phantomjs shine above the other is its lack for requiring xvfb and a browser like Firefox. Starting with version 1.5.0, phantomjs de-coupled itself from xvfb and runs completely independent from it. What does this mean for developers? Fast test execution. It no longer has to wait for Firefox to start up which takes seconds away from your execution. Also, it runs JavaScript specific Cucumbers and Jasmine tests faster than the xvfb solution.

Ariya Hidayat, the author of phantomjs has done a great job with this project. It’s super simple to set up on your Mac OS X, Linux, and Windows environment. Simply download the appropriate binary, tar it to a directory, and symlink the phantomjs binary to a location in your PATH. If you’re on Mac OS X like me and have homebrew installed, then it’s even easier. brew install phantomjs.

Run phantomjs and you should see the REPL:

phantomjs is one of the two solutions I’m aware of that solves the headless browser problem. What makes phantomjs shine above the other is its lack for requiring xvfb and a browser like Firefox. Starting with version 1.5.0, phantomjs de-coupled itself from xvfb and runs completely independent from it. What does this mean for developers? Fast test execution. It no longer has to wait for Firefox to start up which takes seconds away from your execution. Also, it runs JavaScript specific Cucumbers and Jasmine tests faster than the xvfb solution.

Ariya Hidayat, the author of phantomjs has done a great job with this project. It’s super simple to set up on your Mac OS X, Linux, and Windows environment. Simply download the appropriate binary, tar it to a directory, and symlink the phantomjs binary to a location in your PATH. If you’re on Mac OS X like me and have homebrew installed, then it’s even easier. brew install phantomjs.

Run phantomjs and you should see the REPL:
