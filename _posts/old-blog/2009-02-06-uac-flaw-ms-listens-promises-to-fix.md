---
layout: post
published: true
title: UAC Flaw - MS listens, promises to fix.
date: '2009-02-06 11:03:51 +0000'
---

Good news on the [User Access Control flaw](https://alanfleming.org/2009-02-01-uac-flaw-by-design-says-microsoft.html)
I wrote about a few days ago - the Windows 7 engineers have [promised to fix it](http://blogs.msdn.com/e7/archive/2009/02/05/uac-feedback-and-follow-up.aspx)
in the release candidate, and have gone even further in the fix than was asked.

The additional proposal is to run the User Access Control panel in a
mode where other programs cannot manipulate it without first gaining
elevated rights. This should put and end to any potential exploit via
this route.

Good to see the engineers responding to this. The fact that they had to,
however, leads me to wonder if they're not a little insulated --– they
talked about "Customer Driven Engineering" in their previous post [clarifying their views on the flaw](http://blogs.msdn.com/e7/archive/2009/02/05/update-on-uac.aspx)
(now changed of course) but surely a little bit of common sense and
engineering experience should have told them that this was wrong,
regardless of what the behavioural monitoring they performed suggested?
