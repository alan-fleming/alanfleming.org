---
layout: post
published: true
title: User Access Control security flaw in Windows 7 beta
date: '2009-01-30 20:04:04 +0000'
---

[Sacrificing security for usability: UAC security flaw in Windows 7 beta](http://www.istartedsomething.com/20090130/uac-security-flaw-windows-7-beta-proof/):

> By default, Windows 7’s UAC setting is set to “Notify me only when
> programs try to make changes to my computer” and “Don’t notify me when
> I make changes to Windows settings”. How it distinguishes between a
> (third party) program and Windows settings is with a security
> certificate. The applications/applets which manage Windows settings
> are signed with a special Microsoft Windows 7 certificate. As such,
> control panel items are signed with this certificate so they don’t
> prompt UAC if you change any system settings.
>
> The Achilles’ heel of this system is that changing UAC is also
> considered a “change to Windows settings”, coupled with the new
> default UAC security level, would not prompt you if changed. Even to
> disable UAC entirely.

Whoops. This one is a bit of a showstopper. I'm very happy with the
re-imagined User Access Control in Windows 7 (I believe it's pretty much
what it should have been in Vista) but this definitely needs fixed. I
agree completely with Long Zheng's proposed solution:

> Microsoft can implement without sacrificing any of the benefits the
> new UAC model provides, and that is to force a UAC prompt in Secure
> Desktop mode whenever UAC is changed, regardless of its current state.
> This is not a fool-proof solution (users can still inadvertently click
> “yes”) but a simple one.

(Via [I Started Something](http://www.istartedsomething.com).)
