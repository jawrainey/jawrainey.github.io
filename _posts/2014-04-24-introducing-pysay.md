---
layout: post
title: Introducing pysay
color: blue
---

I often found myself using the OS X built-in [say](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/say.1.html) command to hear (_roughly_) how unfamiliar words sound. This was not great as the output of `say` is a robotic voice similar to Microsoft Sam.

Having looked around online I came across [forvo](http://forvo.com) &mdash; a site that contains audio pronunciations of millions of words in their native language. Forvo has pronunciations in [hundreds of languages](http://www.forvo.com/languages-codes/), and provides a _limited_ [REST service](http://api.forvo.com/) (__500__ daily requests).

I decided to create a small command line utility (CLI) that leverages this API as a replacement for the `say` command. This way I can hear how specific _words or phrases_ are meant to be pronounced. Now I can pronounce IKEA furniture names correctly!

Pysay is available on [github](https://github.com/jawrainey/pysay). The [README](https://github.com/jawrainey/pysay/blob/master/README.md) provides installation details and examples. If you have any suggestions for improvements or discover any bugs, feel free to open an [issue](https://github.com/jawrainey/pysay/issues).
