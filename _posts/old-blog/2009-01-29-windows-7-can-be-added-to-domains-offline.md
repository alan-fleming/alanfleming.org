---
layout: post
published: true
title: Windows 7 can be added to domains offline!
date: '2009-01-29 16:37:40 +0000'
---

I have been waiting for this to happen for twelve years, ever since my
first multiple-thousand-seat Windows desktop rollout --- Windows 7 (and
Windows Server 2008 R2) can be added to domains *without physically
being connected to that domain over a network*

This is done with a new command --- djoin.exe --- added into these products.
It's used (on an existing machine in the domain) to generate a block of
information in a file, that can be used on another machine to
automatically join the domain without being connected at that time.

This is fantastically useful for anyone performing big corporate
rollouts --- where it's not always possible to build the machines *in
situ.* Any consultancy working on a build-and-customise desktop project
for a client is going to absolutely love this.

Found on [bink.nu](http://bink.nu).
